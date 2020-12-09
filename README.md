# Predicting-FakeNews
This repository walks you through my methodology for classifying fake news using the Kaggle fake news dataset. In order to replicate this code, the Kaggle and GloVe embeddings data must be downloaded from the link provided (See links below). The Kaggle link will take you to the webpage containing two csv files entitled “Fake.csv” and “True.csv”. The GloVe embeddings link will automatically download a compressed folder. Once you unzip that folder, you should see four text files. The file used for this project is entitled “glove.6B.100d.txt”. 

This notebook (Final.ipynb) is designed to run sequentially. The two sections of the code that will require you to enter paths to the aforementioned files are the “Import data” section and the “Convolutional neural network (Using GloVe word embeddings)” section. In the import data section, you will need to enter a path to the fake news csv file (python variable is named df_fake) and true news csv file (python variable is named df_true). In the “Convolutional neural network (Using GloVe word embeddings)” section, the python variable that locates the unzipped embedding folder is entitled GLOVE_DIR (please note that you should not enter the direct path to the text file of interest, just the folder path). 

Please let me know if you have any issues and happy analyzing! 

## Link to Kaggle fake news dataset can be found here - https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset

## Link to GloVe embeddings can be found here (This link will automatically start a download!!!!!) - http://nlp.stanford.edu/data/glove.6B.zip
