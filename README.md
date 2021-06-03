# MeasNER : Bio NER for Counts and Measurements
[![Built with spaCy](https://img.shields.io/badge/made%20with%20❤%20and-spaCy-09a3d5.svg)](https://spacy.io)

### Disclaimer : Work in progress, doesn't give the best accuracy yet.

![image](https://user-images.githubusercontent.com/34004739/120615321-c75e5d00-c475-11eb-9747-2bec7e2d849d.png)

Trained on MeasEval 2021 SemEval data which focuses on Counts and Measurements entities in clinical texts. (Can be extended to other medical entities as well)

Using PubMedBERT-base-uncased-abstract-fulltext as a backbone so can capture token level information corresponding to medical texts better. 

Trained using spaCy-v3 and can be used directly as a package. 


### Installation 
```
pip install https://github.com/meghanabhange/MeasNER/releases/download/0.1/en_measner-0.1.1.tar.gz
```
