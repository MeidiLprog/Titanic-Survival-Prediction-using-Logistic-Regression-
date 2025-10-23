# Titanic Survival Prediction using Logistic Regression

## Project Overview

This project aims to predict the survival of passengers on the Titanic using logistic regression, a supervised machine learning algorithm suitable for binary classification problems.

The dataset used is the Titanic dataset from Kaggle.

---

## Data Preprocessing

- Handled missing values by filling numeric features with median values.
- Encoded categorical features (`Sex` and `Embarked`) into numeric values using `LabelEncoder`.
- Selected relevant features: `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, `Embarked`.

---

## Model

- Used Logistic Regression to model the probability of survival.
- Split the data into training and validation sets (80/20 split) with stratification to preserve class distribution.
- Trained the model on the training set and evaluated on the validation set.
- After validation, retrained the model on the full training dataset to make predictions on the test set.

---

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score

These metrics help to understand the model's performance beyond just accuracy, especially useful for imbalanced classes.

---

## Results

Achieved an accuracy score of approximately **0.7679** on the Kaggle leaderboard.

---

## How to Run
1. Ensure all dependencies are installed (`scikit-learn`, `pandas`, `numpy`).
2. Run the notebook in a Python environment.
3. The notebook outputs a `submission.csv` file ready for Kaggle submission.
---

## Mathematical Explanation

(Logistic regression formula and explanation here in LaTeX or plain English if you want to include it.)

---

## Author

**Meidi lefki**

---
u
