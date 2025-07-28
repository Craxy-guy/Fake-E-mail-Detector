# Fake Email Detector

The Fake Email Detector is a machine learning-based web application designed to classify email messages as either genuine or fake/spam. Built using Python, it leverages natural language processing (NLP) to clean and analyze the email content, applying techniques like tokenization, stemming, and TF-IDF vectorization. To improve model performance, the dataset is balanced using SMOTE, and a Logistic Regression model is trained for classification. The app is deployed using Gradio, providing a user-friendly interface where anyone can input a message and instantly get a prediction. The model is trained on the well-known SMS Spam Collection Dataset, and proper credit is given to the original data source.


**# How It Works**

This project is a Fake Email Detector that uses Machine Learning to identify whether an email message is genuine or fake/spam. It is trained on the popular SMS Spam Collection Dataset using natural language processing (NLP) techniques and classification algorithms.

**# Key Features:**
Preprocesses text using tokenization, stopword removal, stemming, and TF-IDF vectorization.

Balances the dataset using SMOTE to improve accuracy.

Trains a Logistic Regression model to classify messages.

Deploys a simple Gradio web app for live input and prediction.

**# Tools & Libraries Used:**

1)Python

2)scikit-learn

3)imbalanced-learn (SMOTE)

4)nltk

5)Gradio (for web interface)

Just input your email/message into the Gradio interface, and the model will tell you whether it’s likely Fake/Spam or Genuine.
