Day 4: Fake News Detection
Description

This project focuses on detecting fake news using Logistic Regression as a classification model.
It’s part of my 50 Days of ML challenge.
Dataset

    Source: Originally from Kaggle (Fake News Dataset)

    Data includes both fake and true news articles.

    Main fields: title, text, and label (fake = 0, true = 1)

Objectives

    Load and merge the fake and true datasets

    Clean the text data (remove stopwords, apply stemming, etc.)

    Convert text into numerical form using TfidfVectorizer

    Train a Logistic Regression model

    Evaluate using accuracy, confusion matrix, and classification report

Files

    fake_news_detection.ipynb — main notebook

    README.md — this file

Learnings

    Practiced text preprocessing and NLP pipeline

    Learned how to apply TF-IDF to convert text to vectors

    Gained hands-on experience with Logistic Regression on a real-world problem

    Understood how to evaluate a binary classification model