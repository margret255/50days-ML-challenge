Day 12: Spam Mail Detection using Naive Bayes Classifier

🧾 Description
This project classifies emails as spam or not spam using a Naive Bayes Classifier.
It is part of my 50 Days of Machine Learning challenge and demonstrates how Natural Language Processing (NLP) techniques can be applied to text classification problems.

📊 Dataset

Source: Kaggle – Spam/Ham Email Dataset

Features: Email text content (raw text)

Target: label — Spam or Ham (Not Spam)

🎯 Objectives

Load and explore the email dataset

Clean and preprocess text (stopword removal, tokenization, stemming/lemmatization)

Convert text into numerical features using TF-IDF Vectorization

Train a Naive Bayes model for classification

Evaluate performance using Accuracy, Precision, Recall, and F1-score

📂 Files

spam_mail_detection_dayX.ipynb — main notebook

README.md — this file

🛠️ Tools Used

Python (pandas, numpy)

scikit-learn (CountVectorizer/TF-IDF, MultinomialNB, train_test_split, metrics)

nltk/spacy (for text preprocessing)

matplotlib & seaborn (for visualizations)

✅ Learnings

Learned how to preprocess text data for NLP tasks

Understood the effectiveness of Naive Bayes in spam detection

Gained experience with TF-IDF vectorization

Improved skills in evaluating classification models