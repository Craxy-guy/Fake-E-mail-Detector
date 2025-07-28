# Fake Email Detector

**# How It Works**

This project is a Fake Email Detector that uses Machine Learning to identify whether an email message is genuine or fake/spam. It is trained on the popular SMS Spam Collection Dataset using natural language processing (NLP) techniques and classification algorithms.

**Key Features:**
Preprocesses text using tokenization, stopword removal, stemming, and TF-IDF vectorization.

Balances the dataset using SMOTE to improve accuracy.

Trains a Logistic Regression model to classify messages.

Deploys a simple Gradio web app for live input and prediction.

**Tools & Libraries Used:**
Python

scikit-learn

imbalanced-learn (SMOTE)

nltk

Gradio (for web interface)

Just input your email/message into the Gradio interface, and the model will tell you whether it’s likely Fake/Spam or Genuine.

# How to Run

```bash
pip install -r requirements.txt
python app.py
