# SentimentAnalysis-TopicModeling
Sentiment Analysis &amp; Topic Modeling in Python using Yelp Reviews

# Overview
This project uses Google Colab to run the notebooks and these connect to Google Drive for reading/writing csv files. The notebooks read inputs and generate outputs using this path found in the path variable: 'gdrive/My Drive/GH_NLP_Course/Data/'. This can be changed in the notebooks to reflect any path on your Google Drive.

# Data Source
The data source used (1.input_data.csv) is a slice of the Yelp dataset (https://www.yelp.com/dataset): Yelp reviews and associated ratings for restaurants, from 2017, from the city of Glendale, AZ.

# Project Outline
The project has the following structure:
1. Dataset EDA, Tokenization, Text Normalization (remove punctuation, stemming, etc.)
2. Lexical complexity (Word Frequency, Word Length, Lexical Diversity, Lexical Density)
3. Text Representation (BOW, TF-IDF, Word2Vec, FastText)
4. Model Implementation 1 w ML (Classification)
5. Model Implementation 2 w Lexicon (Rule-based approach)
6. Topic Modeling (Unsupervised: LDA & K-Means Clustering)
