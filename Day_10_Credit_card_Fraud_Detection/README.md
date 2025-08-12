Day 6: Credit Card Fraud Detection using Logistic Regression
🧾Description

This project focuses on detecting fraudulent credit card transactions using Logistic Regression.
It is part of my 50 Days of Machine Learning challenge and aims to classify transactions as fraud or legitimate based on transaction features.
📊 Dataset

    Source: Kaggle Credit Card Fraud Detection Dataset

    Features: 30 variables including Time, Amount, and anonymized numerical features (V1 to V28) obtained through PCA transformation

    Target:

        0 → Legitimate Transaction

        1 → Fraudulent Transaction

🎯 Objectives

    Load and explore the dataset

    Handle class imbalance using undersampling or oversampling

    Split data into training and testing sets

    Train a Logistic Regression model

    Evaluate the model using accuracy, precision, recall, and F1-score

📂 Files

    fault_credoit_card.ipynb

    README.md

🛠️ Tools Used

    Python (pandas, numpy)

    scikit-learn (LogisticRegression, train_test_split, metrics)

    matplotlib & seaborn (for visualizations)

✅ Learnings

    Learned how Logistic Regression works for binary classification problems

    Understood how to handle imbalanced datasets

    Gained insights into precision and recall as important metrics in fraud detection

    Noted the importance of minimizing false negatives in fraud cases

    Practiced evaluating models using confusion matrix and classification report