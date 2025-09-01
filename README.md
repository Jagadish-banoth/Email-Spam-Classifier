## Email Spam Classifier

An Email Spam Classifier built using Machine Learning to detect whether an email is Spam or Ham (Not Spam).

Project Overview

Spam emails are one of the biggest challenges in digital communication. This project uses Natural Language Processing (NLP) techniques and Machine Learning algorithms to classify emails as spam or ham.

The model is trained on a labeled dataset of emails, processes the text, and learns patterns that distinguish spam messages (like "Win a lottery", "Claim free offer") from normal emails.

Tech Stack:

Programming Language: Python

Libraries:

scikit-learn (Machine Learning)

NLTK (Text Preprocessing)

pandas & numpy (Data Handling)

streamlit (Web App for Deployment)

-->Features:

Text preprocessing (tokenization, stopword removal, stemming)

Feature extraction using CountVectorizer / TfidfVectorizer

ML models: Naïve Bayes, SVM, Logistic Regression

Streamlit-based simple web interface for email classification

--> How It Works

Input email text into the web app.

Text is preprocessed and transformed into numerical features.

Model predicts whether the email is Spam or Ham.

--> Model Performance

Accuracy: ~97% (Naïve Bayes)

Precision & Recall optimized for spam detection

 --> With this project, I learned how to apply NLP + ML to solve real-world problems like spam detection.
