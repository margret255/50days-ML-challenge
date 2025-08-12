Day 11: Medical Cost Insurance Prediction using Linear Regression
🧾Description

This project predicts the medical insurance cost of individuals based on personal attributes using Linear Regression.
It is part of my 50 Days of Machine Learning challenge and demonstrates how regression models can be applied to cost prediction problems.
📊 Dataset

    Source: Kaggle Medical Cost Personal Dataset

    Features:

        age — Age of the individual

        sex — Gender of the individual

        bmi — Body Mass Index

        children — Number of children/dependents covered by the insurance

        smoker — Smoking status

        region — Residential area

    Target:

        charges — Individual medical costs billed by health insurance

🎯 Objectives

    Load and explore the insurance dataset

    Encode categorical variables (e.g., sex, smoker, region)

    Split data into training and testing sets

    Train a Linear Regression model

    Evaluate the model using R² score and Mean Absolute Error (MAE)

📂 Files

    medical_cost_insurance_linear_regression_day11.ipynb — main notebook

    README.md — this file

🛠️ Tools Used

    Python (pandas, numpy)

    scikit-learn (LinearRegression, train_test_split, metrics)

    matplotlib & seaborn (for data visualization)

✅ Learnings

    Strengthened understanding of Linear Regression for predicting continuous variables

    Learned how to handle categorical data with encoding techniques

    Practiced evaluating regression models with R² and MAE

    Observed how lifestyle factors (like smoking) strongly influence medical insurance charges