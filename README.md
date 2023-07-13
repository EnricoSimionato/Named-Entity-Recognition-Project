# Named-Entity-Recognition-Project

## Project purpose and explaination
The main purpose of the project is to perform named-entity recognition from Italian documents of different datasets.
Moreover other information entraction techniques have been applied on the datasets.
In the project the KIND (Kessler Italian Named-entities Dataset) is used. It is a dataset released in 2022 by researchers from Fondazione Bruno Kessler and the University of Trento. It contains 1 million tokens, of which 600K name-entities are manually annotated.

In order to perform named-entity recognition in the project CRFs and transformers models are used and then compared. The project is interesting because there are not many useful datasets available to train NER models in the Italian language.

The project is done as part of the exam of the "Natural Language Processing" course at Politecnico di Milano.

## Content explaination
### Notebook directory
The [notebook directory](https://github.com/EnricoSimionato/Named-Entity-Recognition-Project/tree/master/notebook) contains the main file of the project.

The entire project is contained and explained in the file NER_on_KIND_dataset.ipynb. <br> It can be easily loaded and used on Google Colab (https://colab.research.google.com/).

### Datasets directory
The [datasets directory](https://github.com/EnricoSimionato/Named-Entity-Recognition-Project/tree/master/datasets) contains the datasets used in the task and also some files containing sets of names of known entities.
### Docs directory
The [docs directory](https://github.com/EnricoSimionato/Named-Entity-Recognition-Project/tree/master/docs) contains the assignment of the project.
### Model evaluation directory
The [model evaluation directory](https://github.com/EnricoSimionato/Named-Entity-Recognition-Project/tree/master/model%20evaluation) contains some files regarding the performances of the models on the NER task.
### Pos tags directory
The [pos tags directory](https://github.com/EnricoSimionato/Named-Entity-Recognition-Project/tree/master/pos%20tags) contains the part-of-speech tags for the datasets that are used in the project.

## Contributors
The project is realized by:
- Elia Feltrin (https://github.com/EliaFeltrin),
- Enrico Simionato (https://github.com/EnricoSimionato),
- Michael Vitali (https://github.com/MichaelVitali)

## Credits
The KIND dataset, explained in the following can be found at https://github.com/dhfbk/KIND.

The related paper can be found at https://arxiv.org/abs/2112.15099.
