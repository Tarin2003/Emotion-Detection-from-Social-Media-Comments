# Emotion Detection from Social Media Comments

Emotion detection based on text, which includes the following steps:

## Data Collection: 

We created our own dataset by compiling data from YouTube, Instagram, Facebook, Twitter, and Facebook. Two groups have been established for the datasets: train (80%) and test (20%). 4867 text data points make up the Collected dataset in Data Pre-Processing. Four classes— happiness, sadness, anger, and surprise are present in the dataset. Emotions such as happiness, anger, sadness, and surprise are collected as raw data.

## Data Preprocessing:

The data is cleaned by removing HTML tags, URLs, punctuation, numbers, stopwords, and extra whitespaces to ensure proper text formatting.

## Feature Extraction:

Text features are extracted using methods like TF-IDF (Term Frequency-Inverse Document Frequency) and Count Vectorizer.

## Data Splitting:

The processed data is split into training and testing sets.

## Machine Learning & Deep Learning Algorithms:

A variety of algorithms are applied, including SVM, KNN, Decision Trees, Random Forests, AdaBoost, Naive Bayes, Logistic Regression, LSTM, CNN, XGBoost, and others.
Voting methods (hard and soft) are used to enhance model performance.

## Model Training:

The chosen algorithms are trained on the training data.

## Output:

The trained model generates predictions (output).

## Performance Evaluation:

The model's performance is evaluated using metrics like Accuracy, Precision, Recall, and F1-Score.
