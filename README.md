# Credit Card Fraud Detection System
---

## Overview

Credit card fraud is a critical challenge faced by financial institutions worldwide. This project leverages machine learning techniques to classify transactions as fraudulent or legitimate. The models are trained on anonymized transaction data to ensure privacy while achieving high accuracy and reliability.

---

## Dataset

- **Source:** [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Size:** 280K+ transactions with labeled data ('Fraud' or 'Legit').
- **Features:** Includes numerical features (V1-V28), transaction amount, and class labels.

---

## Technologies Used

- **Programming Language:** Python
- **Libraries:**
  - NumPy
  - Pandas
  - Matplotlib
  - Seaborn
  - Scikit-learn
- **Tools:**
  - Jupyter Notebook for analysis and model development.
  - GitHub for version control.

---

## Key Features

1. **Data Preprocessing:**
    - Handling class imbalance using the undersampling technique.
    - Feature scaling to standardize transaction amounts and anonymized variables.

2. **Modeling:**
    - Logistic Regression (baseline model)
    - Random Forest (hyperparameters tuned model)

3. **Evaluation:**
    - Stratified splitting to ensure balanced class representation in training/testing sets.
    - Metrics: Area Under Precision-Recall Curve (AUPRC) score, Precision, and Recall.

4. **Visualization:**
    - Confusion Matrix Correlation Heatmap, Feature Importance Bar Chart

---

## Model Evaluation Metrics

- **AUPRC Score:** 0.99
- **Precision:** 0.96
- **Recall:** 0.94

These metrics ensure minimal false positives and negatives, crucial in fraud detection scenarios.

---

## Project Workflow

1. **Exploratory Data Analysis (EDA):**
Understand the dataset distribution and detect patterns in fraudulent transactions.

2. **Data Preprocessing:**
Handle missing values, class imbalance, and scale features.

3. **Model Training:**
Train baseline model with Logistic Regression and Random Forest model with hyperparameter tuning.

4. **Model Evaluation:**
Evaluate using precision, recall, and AUPRC score.

5. **Optimization:**
Fine-tune parameters and optimize for deployment readiness.
