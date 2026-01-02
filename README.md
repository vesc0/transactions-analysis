# Fraud Detection in Financial Transactions

A Python-based project that analyzes simulated financial transaction data with the goal of detecting fraudulent activity. It leverages statistical techniques, machine learning models, and insightful visualizations to extract and analyze patterns in the data.

Dataset: [Kaggle](https://www.kaggle.com/datasets/vardhansiramdasu/fraudulent-transactions-prediction?select=Fraud.csv)

---

## Contents

- [Dataset](#dataset)
- [Methods](#methods)
- [Key Challenges](#key-challenges)
- [Results](#results)
- [Tools](#tools)

---

## Dataset
- Simulated transactions over 30 days (hourly resolution)
- Highly imbalanced dataset (~0.13% fraud)
- Features include transaction type, amount, balances, and time step

## Methods
- Exploratory Data Analysis (EDA)
- Feature engineering
- Machine Learning models:
  - Random Forest
  - XGBoost
  - Logistic Regression

## Key Challenges
- Extreme class imbalance
- High false-positive rate
- Trade-off between precision and recall

## Results
Models achieve very high recall for fraud detection, demonstrating the difficulty of minimizing false positives in real-world fraud detection systems.

## Tools
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Google Colab
