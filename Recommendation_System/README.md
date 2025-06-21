# Recommendation System using Collaborative Filtering

This project is part of the **CODTECH Machine Learning Internship – Task 4**. It involves building a **Recommendation System** using **Collaborative Filtering** and optionally, **Matrix Factorization (SVD)** techniques.

---

## Task Objective

> Build a recommendation system using Collaborative Filtering or Matrix Factorization to suggest relevant items (e.g., movies) to users based on historical ratings.

---

##  Project Structure

```text
├── recommendation_system.ipynb # Jupyter Notebook with full implementation
├── ratings.csv # Sample dataset (userId, movieId, rating)
├── README.md # Project documentation
```


---

##  Dataset

- **File**: `ratings.csv`
- **Columns**:
  - `userId`: Unique user identifier
  - `movieId`: Unique item (e.g., movie) identifier
  - `rating`: Users rating of the item

Sample dataset source:
- [MovieLens 100K](https://grouplens.org/datasets/movielens/100k/)

---

## Libraries Required

```bash
pandas
numpy
scikit-learn
```

## How to Run

1. Clone this repository

2. Ensure ratings.csv is present in the same directory

3. Run the notebook:

```bash
jupyter notebook recommendation_system.ipynb
```
