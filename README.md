# Twitter Sentiment Analysis
Built a Twitter Sentiment analysis model using NLP and Logistic Regression. Dataset used was: https://www.kaggle.com/datasets/kazanova/sentiment140

# Project Overview
In this project, the model is trained on 1.6 million tweets, labeled as positive (0) and negative (4) which was renamed to 1 in the project. Used NLP to clean the tweets and used Porter Stemmer to stem the tweets and then input into Logistic regression after the text was converted into vectors using TFIDF vectorizer. Model was then trained and returned an accuracy score of 77.8%.

# Key Features
✔ Cleaned the text using NLTK

✔ Converted the cleaned text to numerical values

✔ Trainin the model on vectors

✔ Accuracy score of 77.8% on the testing data


# Tech Stack
Numpy, Pandas, re, pickle, Scikitlearn, NLTK
