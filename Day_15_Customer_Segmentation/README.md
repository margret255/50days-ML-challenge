Day 15: Customer Segmentation using K-Means

🧾 Description
This project performs customer segmentation by grouping customers into distinct clusters based on their behavior and attributes using the K-Means clustering algorithm.
It is part of my 50 Days of Machine Learning challenge and demonstrates how unsupervised learning can help businesses understand their customers for better decision-making and targeted marketing.

📊 Dataset

Source: Kaggle – Mall Customer Segmentation Dataset

Features:

CustomerID — Unique ID for each customer

Gender — Male/Female

Age — Age of the customer

Annual Income (k$) — Annual income in thousand dollars

Spending Score (1-100) — Score assigned based on spending behavior

Target: No explicit target (unsupervised) — the aim is to group customers into clusters.

🎯 Objectives

Load and preprocess the dataset

Perform feature scaling to ensure fair distance calculation

Use the Elbow Method and Silhouette Score to find the optimal number of clusters

Train and apply K-Means clustering

Visualize customer segments

Interpret cluster profiles (e.g., budget shoppers, big spenders, loyal customers)

📂 Files

customer_segmentation_kmeans_day15.ipynb — main notebook

README.md — this file

🛠️ Tools Used

Python (pandas, numpy)

scikit-learn (StandardScaler, KMeans, silhouette_score)

matplotlib & seaborn (for visualization)

✅ Learnings

Understood the importance of scaling for distance-based algorithms

Learned how K-Means works (assignment and centroid update steps)

Practiced using the Elbow Method and Silhouette Score to choose the right number of clusters

Gained insights into unsupervised learning for real-world business applications