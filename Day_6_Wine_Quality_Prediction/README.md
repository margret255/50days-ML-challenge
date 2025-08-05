Day 5: Wine Quality Prediction
Description

This project focuses on predicting the quality of wine based on its physicochemical properties using Decision Tree and Random Forest classifiers.
It’s part of my 50 Days of ML challenge.
Dataset

    The dataset contains various physicochemical attributes (like acidity, sugar, pH, etc.) of red wine samples and their corresponding quality ratings (0–10).

    Source: UCI Machine Learning Repository – Wine Quality Data Set

Objectives

    Load and explore the dataset

    Clean the data and handle missing values if any

    Apply feature engineering and transformations

    Encode target labels using Label Binarization

    Use lambda functions for quick data transformations

    Train classification models: Decision Tree and Random Forest

    Evaluate models using accuracy, confusion matrix, and classification report

    Save the best model using joblib or pickle

Files

    wine_quality_prediction.ipynb — main notebook

    model.pkl — trained Random Forest model

    README.md — this file

Learnings

    How to use lambda functions for quick feature transformation

    Label Binarization for converting wine quality into binary classification

    Decision Tree vs Random Forest: key differences in accuracy and overfitting

    Importance of feature selection in boosting model performance

    Model evaluation metrics for classification problems
