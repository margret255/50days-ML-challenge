Day 7: Car Price Prediction using Linear & Lasso Regression
🧾Description

This project focuses on predicting the price of cars based on various features using Linear Regression and Lasso Regression models.
It is part of my 50 Days of Machine Learning challenge and explores how different regression techniques perform on a real-world dataset.
📊 Dataset

    Source: https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho

    Features: Variables like brand, mileage, year, engine size, fuel type, transmission, etc.

    Target:
        price 

🎯 Objectives

    Load and explore the car dataset

    Preprocess the data (handle missing values, encode categorical data, feature scaling)

    Split data into training and testing sets

    Train and evaluate a Linear Regression model

    Train and evaluate a Lasso Regression model

    Compare the performance of both models using R² score and MAE

📂 Files

    car_price_prediction.ipynb — main notebook

    README.md — this file

🛠️ Tools Used

    Python (pandas, numpy)

    scikit-learn (LinearRegression, Lasso, train_test_split, StandardScaler, metrics)

    matplotlib & seaborn (for visualizations)

✅ Learnings

    R² score is a key metric for regression problems (indicates how well the model fits the data)

    Accuracy is used for classification problems, not regression

    Linear Regression works best when features are directly related to the target

    Lasso Regression can be useful when dealing with many features and for automatic feature selection (by shrinking coefficients to zero)

    Learned to compare models and choose the one with better generalization