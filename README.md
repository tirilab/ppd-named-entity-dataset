# Postpartum Depression Named Entity Dataset

We created a dataset of postpartum depression (PPD) forum threads with biomedical term annotations. 

## Data
This corpus includes pre-processed 10,548 BabyCenter.com forum threads (posts and comments) and [MMLite](https://metamap.nlm.nih.gov/MetaMapLite.shtml) annotations. 

The "PPD-NER-Corpus-1.0" folder contains pre-processed text files for each PPD forum thread (.txt files), annotation files (.ann files), and the MMLite configuration file (annotation.conf). 

## Preparation
MMLite[1] was used to annotate biomedical terms from the following BabyCenter.com public online health community discussion boards:
* Postpartum Depression, Anxiety and Related Topics [[Internet](https://community.babycenter.com/groups/a15325)]. BabyCenter Community. (cited 2018May9)
* Postpartum Depression and Postpartum Anxiety Support Group [[Internet](https://community.babycenter.com/groups/a6742129)]. BabyCenter Community. (cited 2018May9)
* POSTPARTUM ANXIETY SUPPORT GROUP [[Internet](https://community.babycenter.com/groups/a6718921)]. BabyCenter Community. (cited 2018May9) 

1. Demner-Fushman D, Rogers WJ, Aronson AR. MetaMap Lite: an evaluation of a new Java implementation of MetaMap. Journal of the American Medical Informatics Association. 2017 Jan 27;24(4):841-4.

## License and Citation
Data can be used as-is under the [MIT License](https://github.com/translational-informatics/ppd-named-entity-dataset/blob/master/LICENSE) attached to the repository. Please cite this article if using this data set:

Chowdhuri S, McCrea S, Demner-Fushman D, Taylor CO. Extracting Biomedical Terms from Postpartum Depression Online Health Communities. In AMIA Summits on Translational Science Proceedings, vol. 2019 (accepted).
