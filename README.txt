README

Files
------
Weighted_Ensemble.ipynb: an attempt at creating a weighted ensemble model
venueBERT.ipynb: training the SciBERT on the venue feature
graphsage.ipynb: building the GraphSage model for the authors feature
exploring_dataset.ipynb: exploratory data analysis of the dataset
ensemble.ipynb: majority voting and averaging ensemble with the SciBERT-based models
creating_dataframe.ipynb: converting the original data into more usable form
bert_title_abstract.ipynb: building SciBERT-based models for title and abstract feature

Hyperparams
------------

TitleBERT
Batch size = 256
Epochs = 1
Learning rate = 1e-3
Optimizer = AdamW

VenueBERT
Batch size = 128
Epochs = 1
Learning rate = 1e-3
Optimizer = AdamW

AbstractBERT
Batch size = 256
Epochs = 1
Learning rate = 1e-3
Optimizer = AdamW

AuthorsGS
Batch size = 40
Epochs = 10
Layer size = 20, 20
Learning rate = 1e-3
Optimizer = Adam
