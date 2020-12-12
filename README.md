## RecSys
# Recommender System
The movie dataset is downloaded from Kaggle (https://www.kaggle.com/rounakbanik/the-movies-dataset). To upload it in google colab:

1. Go to your Kaggle account 

1a. In API section, "Create New API Token". 

1b. 'kaggle.json' file will be downloaded

2. Upload your API token in colab

3. Set the path for json file

import os

os.environ['KAGGLE_CONFIG_DIR']="<path of your kaggle.json file>"

4. Download the movie dataset

!kaggle datasets download -d rounakbanik/the-movies-dataset

5. The file downloaded will be in zip format. so unzip it 

!unzip "<path of your zip file(movie dataset)>" -d "<place you want to unzip>"
  
for more unzip:
(https://colab.research.google.com/drive/1xinRwhXtlL-9Y0KbPrTmTxNdcN-Hvq4m#scrollTo=O1_kc7HBeslm)
