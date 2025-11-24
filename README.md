# Spam-Mail-Classifier
# Overview of the project
-A Spam Mail Classifier is a Machine Learning (ML) system that automatically identifies whether an incoming email or SMS message is Spam ( harmful) or Fraud.
# Features
1. SMS Spam Detection
2. this project focuses on SMS spam detection.
classifies:
Spam
fraud
3.  project includes  function (clean_text) that performs:
Lowercasing
Removing URLs
Removing numbers
Removing punctuation
Collapsing extra spaces
This improves model accuracy and is visible in preprocess.py.
4. Prediction Module
Your file predict.py includes:
Loading saved model
Predicting new messages
Returning SPAM or HAM
This enables real-time inference.
# Technology/tools used
1. Programming Language
 Python
Used for:
Data loading
Text preprocessing
Model training
Evaluation
Web application
Saving/loading model
2. Development Environment / Editors
 Jupyter Notebook
Used for writing and running Python scripts.
3. Libraries & Frameworks (Python)
A. Data Handling
pandas → loading CSV dataset
numpy → numerical operations
B. Machine Learning
C. Web Application
Flask
Used to build the simple web interface where user enters SMS and gets prediction.
E. Testing
pytest
Used for simple unit testing (test_preprocess.py).
4. NLP (Natural Language Processing) Tools
TF-IDF Vectorizer
Converts text into numerical features based on term importance.
Text Preprocessing Tools
Regex
Punctuation removal
Lowercasing
Whitespace normalization

These steps are implemented in preprocess.py.

5. Dataset Tools

CSV Format (Comma-Separated Values)
The dataset (sms_spam_sample.csv) is stored and loaded in CSV form.

6. Project Management Tools

Git (optional)
For version control.

GitHub (optional)
For hosting code online.

7. Operating System Compatibility

Your project works on:

Windows

Linux

macOS

Because all tools used are cross-platform.

8. Browser (For Web App Testing)

Google Chrome

Mozilla Firefox

Microsoft Edge

(As required by your college submission guidelines.)

