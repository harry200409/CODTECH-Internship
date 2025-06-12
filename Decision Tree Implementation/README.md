# Task-1: Decision Tree Classifier with Visualization

This project is part of the **Machine Learning Internship (CODTECH)**. It focuses on building and analyzing a Decision Tree model using **scikit-learn** on the **Iris dataset**.

---

##  Task Objective

> Build and visualize a Decision Tree model using `scikit-learn` to classify or predict outcomes on a chosen dataset.

---

##  Project Structure

```text
├── decision_tree_iris.ipynb # Jupyter notebook with full code and visualizations
├── README.md # This file

```


---

##  Dataset

We use the **Iris dataset**, a classical dataset for classification tasks. It contains:
- 150 samples
- 4 features: sepal length, sepal width, petal length, petal width
- 3 target classes: Setosa, Versicolor, Virginica

---

##  Tools & Libraries

- Python
- pandas
- numpy
- matplotlib & seaborn
- scikit-learn

---

##  Workflow & Analysis

###  Step-by-step:
1. Load the Iris dataset
2. Preprocess and split data into training/test sets
3. Train a Decision Tree model
4. Make predictions
5. Evaluate with:
   - Accuracy
   - Precision, Recall, F1 Score
   - Confusion Matrix
   - Cross-validation
6. Visualize:
   - Decision Tree structure
   - Feature Importance
   - Decision boundaries (2D)
   - Learning curve

---

##  Key Insights

- **Petal length and width** are most important for classification.
- Decision Tree achieved **high accuracy** with default parameters.
- Comparison between `gini` and `entropy` showed similar performance.
- Learning curve indicates that the model performs well without overfitting.

---

##  Instructions

To run the notebook:

1. Clone this repository
2. Install dependencies using:
   ```bash
   pip install -r requirements.txt
3. Open the Jupyter notebook:
   ```bash
   jupyter notebook decision_tree_iris.ipynb

   
## Deliverable
A well-commented Jupyter Notebook showcasing:

Decision Tree model

Visualizations

In-depth analysis
