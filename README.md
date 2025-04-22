# Movie Recommendation System

## Project Overview

Streaming users spend over **110+ hours per year** scrolling to find content, leading to frustration and high subscription churn.  
This project builds a **Movie Recommendation System** to address that problem by **reducing scroll time and improving user satisfaction**.

Using the **[MovieLens 1M dataset](https://grouplens.org/datasets/movielens/1m/)**, I developed, compared, and evaluated multiple recommendation models, focusing on both technical performance and real-world business impact.

**[Project Code Here](https://github.com/sarahberkin/Movie-Recommendation-System-Capstone-Berkin/blob/main/Final_Movie_Recommender_Capstone.ipynb)**

---

## Data and Features

- **Dataset:** MovieLens 1M
- **Users:** 6,000+
- **Movies:** 4,000+
- **Ratings:** 1 million+ explicit ratings (scale 0.5–5.0)

### User Features:
- Gender
- Age Group
- Occupation

### Movie Features:
- Genres
- Release Year

---

## Models Built and Evaluated

| Model | Description |
|-------|-------------|
| SVD (Collaborative Filtering) | Matrix factorization model using user-item interactions |
| KNN Regressor | Feature-based distance model |
| Random Forest Regressor | Ensemble model using user and movie features |

---

## Results

| Model | RMSE (Lower = Better) |
|-------|------------------------|
| **SVD** | **0.8869** (Best) |
| KNN Regressor | 1.0165 |
| Random Forest Regressor | 0.9813 |

Behavior simulations showed that the SVD model could predict **10 out of 10 highly-rated recommendations** for random users, significantly reducing scrolling frustration.

---

## Business Value

- Reduce Subscription Churn by Improving Content Discovery
- Increase User Engagement with Personalized Watchlists and Push Notifications
- Targeted Upsell Opportunities Based on User Preferences

---

## Future Improvements

- Quantify **Scroll Time Reduction** (Concrete scroll time tracking)
- Build **hybrid models** (collaborative + content-based) 
- Incorporate **implicit feedback** (e.g., watch time, partial views)
- Add more **user demographic** features if available
- Deploy **A/B testing** to measure real-world impact

---

## Ackowledgements

- MovieLens 1M Dataset — [Grouplens Research](https://grouplens.org/datasets/movielens/1m/)
- Surprise Python Library for Recommender Systems
- Scikit-learn Machine Learning Framework
- Matplotlib and Seaborn for Data Visualization

