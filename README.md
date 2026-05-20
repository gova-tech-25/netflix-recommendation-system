# Netflix Recommendation System

A beginner Machine Learning project that analyzes Netflix movies and TV shows data and builds a content-based recommendation system using NLP techniques.

---

# Project Overview

This project performs:
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Content-Based Recommendation System

The recommendation system suggests similar Netflix titles using:
- TF-IDF Vectorization
- Cosine Similarity

---

# Features

- Analyze Netflix Movies and TV Shows
- Visualize Ratings Distribution
- Explore Top Genres
- Analyze Netflix Content Growth
- Explore Top Countries Producing Content
- Recommend Similar Movies and TV Shows

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# Machine Learning Concepts Used

## TF-IDF Vectorization
TF-IDF converts movie descriptions into numerical vectors so that machine learning algorithms can process text data.

## Cosine Similarity
Cosine similarity measures how similar two movie descriptions are and helps generate recommendations.

---

# Dataset

Dataset used:
Netflix Movies and TV Shows Dataset from Kaggle

Dataset Link:
https://www.kaggle.com/datasets/shivamb/netflix-shows

---

# Project Structure

```text
Netflix-ML-Project/
│
├── data/
│   └── netflix_titles.csv
│
├── notebooks/
│   └── netflix_analysis.ipynb
│
├── images/
│   ├── movies_vs_tvshows.png
│   ├── ratings_distribution.png
│   ├── top_genres.png
│   ├── content_growth.png
│   └── top_countries.png
│
├── README.md
│
└── requirements.txt
```

---

# Exploratory Data Analysis

The project includes visualizations for:
- Movies vs TV Shows
- Ratings Distribution
- Top Genres
- Netflix Content Growth
- Top Countries

---

# Recommendation System

The recommendation system:
1. Converts movie descriptions into vectors using TF-IDF
2. Calculates similarity using cosine similarity
3. Recommends similar Netflix titles

Example:

```python
recommend("Stranger Things")
```

---

# Installation

Clone the repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_LINK
```

Install required libraries:

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

---

# Future Improvements

- Streamlit Web App
- Movie Poster Recommendations
- Genre-Based Filtering
- Improved Recommendation Accuracy
- Deployment

---

# Conclusion

This project demonstrates how NLP and Machine Learning techniques can be used to build a content-based recommendation system using Netflix data.

---

# Author

Dande Govardhan

