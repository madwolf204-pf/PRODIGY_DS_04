# PRODIGY_DS_04

# Twitter Sentiment Analysis of Various Topics

### Overview

This repository details a project focused on performing sentiment analysis on a large corpus of Twitter data related to diverse topics, ranging from tech companies (like Microsoft, Google) to video games (like Borderlands, Fortnite) and streaming services.

The primary goal is to classify the sentiment of tweets as Positive, Negative, or Neutral using machine learning techniques, providing insights into public opinion across different brand and entertainment categories.

### Dataset

The project uses the twitter_training.csv dataset, which contains over 74,000 tweets.

The key columns in the dataset are:

- ID: Unique identifier for the tweet/source.

- Topic: The subject/brand the tweet is about (e.g., "Borderlands," "Nvidia," "TomClancysGhostRecon").

- Sentiment: The target variable to be predicted, categorized as Positive, Negative, or Neutral.

- Text: The content of the tweet itself.

### Methodology

The entire analysis and modeling workflow is contained within the Twitter sentiment analysis Task4.ipynb Jupyter Notebook.

#### Key Steps:

* Exploratory Data Analysis (EDA): Visualizing the distribution of sentiments across all topics and identifying any immediate data quality issues.

* Text Preprocessing: Cleaning the tweet data by handling missing values, tokenization, removing stop words, and potentially stemming or lemmatization.

* Feature Engineering: Converting raw text into numerical features suitable for machine learning, likely using methods like TF-IDF or Count Vectorization.

* Model Training: Training a classification model (e.g., Naive Bayes, Logistic Regression, or a more advanced technique like a Recurrent Neural Network if applicable, based on the notebook content) to predict the sentiment.

* Evaluation: Assessing the model's performance using metrics such as accuracy, precision, recall, F1-score, and a confusion matrix.
