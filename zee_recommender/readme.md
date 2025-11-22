📺 Zee Recommender System

A machine learning–based recommendation engine built to suggest personalized content to users based on their viewing history, similarity patterns, and user–item interactions.

⭐ Project Overview

The Zee Recommender System is designed to recommend movies, shows, or videos from the Zee content library using:

Content-Based Filtering

Collaborative Filtering

Hybrid Recommendation Strategy

This project demonstrates end-to-end data processing, feature engineering, model development, evaluation, and deployment-ready pipeline.

🗂️ Features

✔️ Data cleaning & preprocessing
✔️ Feature engineering (TF-IDF, embeddings, similarity matrices)
✔️ User–Item collaborative filtering (Cosine similarity / KNN)
✔️ Content-based recommendations
✔️ Hybrid recommender output
✔️ Model explainability and evaluation metrics

📁 Project Structure
📦 zee-recommender-system
│

├── dataset
|zee-movies.dat                 # Original dataset
│zee-ratings.dat   
│zee-users.dat

├── notebooks
│zee_recommender_systems.ipynb   
│

📊 Tech Stack

Languages: Python
Libraries:

pandas, numpy

scikit-learn

nltk / spacy

cosine similarity

pickle / joblib

🔧 How It Works
1. Data Preprocessing

Remove missing values

Normalize genres, actors, descriptions

Create TF-IDF vectors for content features

2. Content-Based Filtering

Uses cosine similarity of description, genre, cast, keywords.

3. Collaborative Filtering

User–item matrix
Similarity-based nearest neighbors for recommendations.

4. Hybrid Logic

Weighted combination of content-based and collaborative results.

🚀 Running the Project
Clone the repo
git clone https://github.com/sneha-4515/Data_science_projects/new/main/zee_recommender

OR
open the Jupyter notebooks inside /notebooks.

🧪 Evaluation Metrics

Precision@K

Recall@K

Hit Rate

Coverage

Cosine similarity score visualization

📌 Sample Output

Input: “Comedy, family-friendly, Rohit Shetty movies”
Output:

Golmaal Returns

All the Best

Golmaal 3

Sunday

🗒️ Future Improvements

Add deep-learning recommendations (Neural Collaborative Filtering)

Integrate user behaviour (watch time, likes)

Deploy using AWS / HuggingFace Spaces

🤝 Contributing

Pull requests are welcome!
