# Movie Recommendation System using Hybrid Filtering

## 📌 Overview
This project implements a movie recommendation engine using a hybrid approach that combines collaborative and content-based filtering. The goal is to predict whether a user would enjoy a movie based on their past interactions and the metadata of the movies.

## 📂 Dataset
- Source: [MovieLens Dataset](https://grouplens.org/datasets/movielens/latest/)
- Size: 100,000+ ratings from 600+ users on 9,000+ movies

## 🔧 Technologies Used
- Python, Pandas, Scikit-learn, Surprise
- TF-IDF, Cosine Similarity, SVD

## 🧠 Methodology
- **Content-Based Filtering**: Uses TF-IDF on movie descriptions and cosine similarity to find similar items
- **Collaborative Filtering**: Uses matrix factorization (SVD) to identify patterns in user ratings
- **Hybrid**: Combines both approaches for improved accuracy

## 📊 Evaluation Metrics
- RMSE
- Precision@10
- Recall@10

## 📎 How to Use
1. Clone the repository
2. Install requirements (`pip install -r requirements.txt`)
3. Run `recommendation_model.ipynb`

## 📈 Output
- Personalized movie recommendations
- Evaluation graphs and metrics
