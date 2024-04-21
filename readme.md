## 0. Dataset
- **netflix_titles.csv**: original dataset from kaggle. All TV Shows and Movies meta data on Netflix.

- **preprocessed_netflix_titles.csv**: preprocessed csv dataset.

- **netflix**: preprocessed dataset consisting of a number of individual txt files.

- **vector_db**: Vector database created with the FAISS library

## 1. Preliminary work

- **1.1 Dataset_Preprocess.ipynb**

- **1.2 DatasetOverview_manul.ipynb**: Before using the csv agent to statistically analyse the dataset, we manually performed an exploratory data analysis of the dataset using python to get a full picture of the dataset.

## 2. ChatBot Implementation

- **1.1 EDA_ChatBot.ipynb**: The first chatbot is used for exploratory data analysis of the csv dataset and is able to return overview information and statics visualisation results of the dataset.

- **1.2 IR&Recommend_ChatBot.ipynb**: The second chatbot is used to retrieve files for all movies and TV shows, which can be used for content-based Q&A and also allows the chatbot to complete recommendations for movies based on our needs.