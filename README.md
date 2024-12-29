# Spam Email Classification using NLP and Machine Learning

Project Overview
This project aims to classify emails as Spam or Not Spam using Natural Language Processing (NLP) techniques and Machine Learning algorithms. The system takes an email as input, processes its textual content, and predicts whether it is spam or not.

The project involves:

1.Feature extraction from textual data using NLP techniques like Count Vectorization or TF-IDF.
2.Model training using Logistic Regression.
3.Deployment of the trained model using Flask for a web-based user interface.

Features
1.Pre-trained Logistic Regression model for spam classification.
2.Web-based UI for entering email content.
3.Uses Flask for backend and Python libraries like sklearn for machine learning.

Tech Stack
Frontend
  1.HTML, CSS for the user interface.
Backend
  1.Flask for server-side logic.
  2.Pickle for model serialization.
Machine Learning
  1.Logistic Regression for classification.
  2.TF-IDF Vectorizer for feature extraction.
Libraries/Tools
  1.Python (3.7+)
  2.NumPy, Pandas, Scikit-learn
  3.Flask
  4.Google Colab for model training

Usage
1.Enter the email text in the provided input box on the web interface.
2.Submit the form to see whether the email is classified as Spam or Not Spam.
3.The model predicts based on the trained Logistic Regression algorithm.

Model Training
The model was trained using the following steps:

  1.Data Preprocessing:
    -Cleaned the email text (removed stopwords, punctuations, and performed stemming).
    -Transformed text data using TF-IDF Vectorizer.
  2.Model Training:
    -Trained a Logistic Regression classifier.
    -Evaluated the model with accuracy, precision, recall, and F1-score.
Model training was performed in the Spam Email Classification Using Python.ipynb file using Google Colab.
