# NER---Movie-Title-Extraction

This repository contains an application Natural Language Processing , using NER model. The result was compared to a customised model using the default NER model from the spaCy package. The model was used to extract movie and television show titles from survey responses of viewers. I used a few examples of entities to train the model. 

NER model accepts training data in list of tuples format. To create a trining set, I have used a spaCy NER Annotator tool from [spaCy NER Annotator](https://manivannanmurugavel.github.io/annotating-tool/spacy-ner-annotator/). The annotating tool generates a json file of trainig set. Once done that, convert_spacy_train_data.py was called to convert the json file into text, which is suitable format for spaCy package.
