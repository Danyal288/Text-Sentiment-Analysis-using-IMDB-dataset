Text-Sentiment-Analysis-using-IMDB-dataset

# Description

This project focuses on building a sentiment analysis model using the IMDB Reviews dataset. The goal is to classify text reviews as positive or negative, leveraging natural language processing (NLP) techniques and machine learning. The final outcome is a Python script that preprocesses input text, predicts sentiment, and provides evaluation metrics.

# Steps

**1. Data Preprocessing**
Import libraries such as nltk, re, and pandas.
Cleaned the text,
Removed HTML tags, URLs, and special characters.
Tokenize the text into individual words.
Removed stopwords (common words with no semantic importance).
Applyed stemming to normalize words.
Checked for duplicates and remove them.

**2. Exploratory Data Analysis (EDA)**
Visualize the distribution of sentiments.
Generated word clouds to highlight frequently occurring terms in positive and negative reviews.

**3. Feature Engineering**
Used the TF-IDF Vectorizer to convert text data into numerical format.
Split the dataset into training and testing subsets for model training.

**4. Model Training and Evaluation**
Trained a Support Vector Classifier (SVC) model for sentiment classification.
Tuned hyperparameters for optimal results.
Evaluated model performance with metrics like confusion matric.

# Finding.
*Key Insight*
Frequent terms in positive reviews include great, amazing, and excellent.
Negative reviews frequently feature bad, worst, and boring.

*Observation*
Proper preprocessing significantly impacts model performance.
SVC performs well with tuned hyperparameters but requires computational resources for larger datasets.
