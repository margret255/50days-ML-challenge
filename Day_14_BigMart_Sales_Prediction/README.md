Day 14: BigMart Sales Prediction using XGBoost

🧾 Description
This project predicts the sales of products across various BigMart outlets using the XGBoost regression algorithm.
It is part of my 50 Days of Machine Learning challenge and demonstrates how boosting algorithms can improve predictive performance for regression problems.

📊 Dataset

Source: Kaggle – BigMart Sales Prediction Dataset

Features:

Item_Identifier — Unique product ID

Item_Weight — Weight of the product

Item_Fat_Content — Low Fat/Regular

Item_Visibility — Visibility score in the store

Item_Type — Type/category of product

Outlet_Identifier — Store ID

Outlet_Size — Store size

Outlet_Location_Type — Tier 1, Tier 2, Tier 3

Outlet_Type — Grocery Store/Supermarket

Target: Item_Outlet_Sales — Sales amount

🎯 Objectives

Load and clean the dataset

Handle missing values and encode categorical variables

Perform feature scaling and transformation

Train an XGBoost regressor model

Evaluate using R² score and RMSE

📂 Files

bigmart_sales_xgboost_dayX.ipynb — main notebook

README.md — this file

🛠️ Tools Used

Python (pandas, numpy)

scikit-learn (train_test_split, metrics)

XGBoost library

matplotlib & seaborn (for visualization)

✅ Learnings

Strengthened skills in gradient boosting techniques

Learned hyperparameter tuning for XGBoost

Understood how store and product attributes affect sales

Practiced handling missing values and categorical encoding