# Twitter Sentiment Analysis

## Introduction

This project focuses on analyzing the sentiment of tweets using machine learning techniques. The dataset used for this project is sourced from Kaggle. The objective is to classify tweets into positive, negative, or neutral sentiments.

## Table of Contents

1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Installation](#installation)
4. [Data Preprocessing](#data-preprocessing)
5. [Modeling](#modeling)
6. [Evaluation](#evaluation)
7. [Results](#results)
8. [Conclusion](#conclusion)

## Dataset

The dataset is sourced from Kaggle and contains tweets with their corresponding sentiment labels. The dataset includes the following columns:

- **id**: Unique identifier for the tweet
- **text**: The text of the tweet
- **target**: The sentiment label (positive, negative)

## Installation

To run this project, you'll need to have Python installed along with several libraries. You can install the required libraries using the following command:
pip install pandas numpy nltk scikit-learn

## Data Preprocessing
The data preprocessing steps involve the following:

1. Loading the dataset: The dataset is loaded into a pandas DataFrame.
2. Text cleaning: The text is cleaned by removing special characters, URLs, and stop words.
3. Tokenization: The text is tokenized into individual words.
4. Stemming: Words are reduced to their root forms.
5. Vectorization: The text data is converted into numerical format using techniques like TF-IDF.

## Modeling
The modeling phase involves training machine learning models to classify the tweets' sentiments. The following models are used:

1. Logistic Regression
2. Support Vector Machine (SVM)
3. Random Forest

The steps include:
1. Splitting the data: The dataset is split into training and testing sets.
2. Training the models: Each model is trained on the training data.

## Evaluation
The models are evaluated using the following metrics:
1. Accuracy
2. Precision
3. Recall
4. F1 Score

## Results
The results of the models are compared, and the best-performing model is selected. The performance metrics are displayed in a tabular format.

Model                 	Accuracy	Precision	Recall	F1 Score
Logistic Regression         0.85	   0.84	   0.85	   0.84
SVM                       	0.88   	 0.87	   0.88	   0.87
Random Forest	              0.86	   0.85	   0.86	   0.85

## Conclusion
The SVM model performed the best in terms of accuracy, precision, recall, and F1 score. Future improvements could include using deep learning techniques and experimenting with different feature extraction methods.
