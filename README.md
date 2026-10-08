# Logistic Regression – Student Pass/Fail Prediction

## 📌 Project Overview

This project demonstrates the use of **Logistic Regression** for a binary classification problem.

The objective is to predict whether a student will **Pass or Fail** based on the number of hours they study.

- **Input Feature:** Study Hours
- **Target Variable:** Student Result
- **0:** Fail
- **1:** Pass

The project follows a complete basic machine learning workflow, including data preparation, train-test splitting, model training, prediction, probability estimation, and model evaluation.

---

## 👨‍🎓 Student Details

**Name:** Pratik Pattewar  
**Student ID:** 2300030969

---

## 🎯 Objective

The main objective of this project is to:

- Understand Logistic Regression for binary classification.
- Train a model using study-hour data.
- Predict whether a student will Pass or Fail.
- Calculate the probability of passing.
- Evaluate the model using classification metrics.
- Visualize the confusion matrix.

---

## 📊 Dataset

The dataset contains study hours and the corresponding student result.

| Study Hours | Result |
|------------:|:------:|
| 1 | Fail |
| 2 | Fail |
| 3 | Fail |
| 4 | Fail |
| 5 | Pass |
| 6 | Pass |
| 7 | Pass |
| 8 | Pass |
| 9 | Pass |
| 10 | Pass |

### Features and Target

**Feature (X):**
- `Study Hours`

**Target (y):**
- `0` → Fail
- `1` → Pass

---

## 🧠 Why Logistic Regression?

Logistic Regression is suitable for this problem because the target variable has two possible classes:

- Fail
- Pass

It is a **supervised machine learning classification algorithm** used to estimate the probability of an observation belonging to a particular class.

---

## 🔄 Machine Learning Workflow

```text
Dataset
   ↓
Data Inspection
   ↓
Check Missing Values & Classes
   ↓
Train-Test Split
   ↓
Train Logistic Regression Model
   ↓
Make Predictions
   ↓
Predict Probability
   ↓
Evaluate Model
   ↓
Confusion Matrix & Classification Report
