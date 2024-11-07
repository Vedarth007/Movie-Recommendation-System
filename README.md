# Movie-Recommendation-System

This project implements a personalized movie recommendation system using multiple techniques, including collaborative filtering, clustering, genre-based recommendations, and recency-frequency boosting. The system is designed to provide tailored movie suggestions to users based on their past interactions and preferences.

## Features

- **Personalized Recommendations**: Suggests movies to users based on their historical data and preferences.
- **Recency and Frequency Boosting**: Movies are recommended with additional weighting based on the recency of interactions and the frequency of user activity.
- **Clustering**: Users are grouped into clusters based on recency and frequency of interactions for more accurate recommendations.
- **Genre-based Recommendations**: Uses genre-based similarity to recommend movies based on user preferences.
- **Explainability**: SHAP values are used to interpret and explain the model's predictions.

## Requirements

- Python 3.x
- Libraries: 
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `scikit-surprise`
  - `faiss-cpu`
  - `shap`
  - `matplotlib`

You can install the required libraries using the following commands:

```bash
pip install pandas numpy scikit-learn scikit-surprise faiss-cpu shap matplotlib
