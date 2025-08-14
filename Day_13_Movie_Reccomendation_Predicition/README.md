Day 13: Movie Recommendation using Collaborative Filtering

🧾 Description
This project recommends movies to users based on past viewing patterns using a Collaborative Filtering approach.
It is part of my 50 Days of Machine Learning challenge and demonstrates how recommendation systems can be built using similarity-based methods.

📊 Dataset

Source: Kaggle – MovieLens Dataset

Features:

userId — ID of the user

movieId — ID of the movie

rating — Rating given by the user to the movie

title — Movie title

Target: Recommended movies for each user

🎯 Objectives

Load and explore the movie ratings dataset

Implement user-based collaborative filtering

Calculate similarity between users/movies

Generate top N recommendations for each user

Evaluate recommendations qualitatively and quantitatively

📂 Files

movie_recommendation_dayX.ipynb — main notebook

README.md — this file

🛠️ Tools Used

Python (pandas, numpy)

scikit-learn (cosine_similarity)

matplotlib & seaborn (for EDA)

✅ Learnings

Understood how collaborative filtering works for recommendation systems

Practiced calculating similarity scores

Learned how to generate personalized recommendations

Explored challenges with cold-start and sparse datasets