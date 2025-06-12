# Task-2: Sentiment Analysis using TF-IDF and Logistic Regression

This project is part of the **CODTECH Machine Learning Internship (Task 2)**. It demonstrates how to build a sentiment analysis pipeline using **Natural Language Processing (NLP)** techniques.

---

## Task Objective

> Perform sentiment analysis on a dataset of customer reviews using **TF-IDF vectorization** and **Logistic Regression**.

---

## Project Structure

```text
├── Sentiment Analysis With NLP.ipynb # Main Jupyter notebook
├── amazon_cells_labelled.txt # Raw dataset (text + sentiment labels)
├── README.md # Project documentation

```
---

## 📝 Dataset Description

- **Source**: `amazon_cells_labelled.txt`  
- **Format**: Tab-separated (`\t`)
- **Columns**:
  - `Review`: Customer feedback (text)
  - `Sentiment`: Label (0 = negative, 1 = positive)

---

## 📊 Techniques Used

- Text cleaning (lowercasing, punctuation removal, etc.)
- Stopwords removal
- TF-IDF vectorization (`TfidfVectorizer`)
- Logistic Regression classifier
- Performance metrics and visualizations

---

## 🧰 Libraries Required

```bash
pandas
numpy
scikit-learn
matplotlib
seaborn
nltk
```

You can install them using:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn nltk
```

## How to Run the Notebook

1. Clone the repository
2. Ensure the dataset file is in the same directory as the notebook
3. Run the notebook:
```bash
jupyter notebook "Sentiment Analysis With NLP.ipynb"
```

## Output Includes

- Accuracy, Precision, Recall, F1-score
- Confusion matrix visualization
- Top TF-IDF features for each sentiment class
