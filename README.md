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
  - Logistic Regression
  - Random Forest
  - XGBoost

## Key Challenges
- Extreme class imbalance
- High false-positive rate
- Trade-off between precision and recall

## Results
- **Logistic Regression:** High recall (≈0.84) but very low precision (≈0.01), limited by linearity.
- **Random Forest:** Relatively high recall (≈0.70) and very high precision (≈0.95).
- **XGBoost:** Very high recall (≈0.93) but low precision (≈0.31).
- Highlights the trade-off between catching all fraud and reducing false positives. Non-linear models perform better as training size increases.

## Tools
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Google Colab
