# SOQ_project
---

## 📊 Machine Learning Projects Portfolio

Welcome to my data science and machine learning project repository. This repo includes two core projects demonstrating practical applications of ML in:

* 📈 **Trading Strategy Backtesting** (EMA + RSI)
* 🔐 **Credit Card Fraud Detection** (Decision Tree & XGBoost)

---

### 🔁 1. Backtest Trading Strategy: EMA + RSI

#### 🧠 Description:

A rule-based trading strategy leveraging:

* **Exponential Moving Average (EMA)**
* **Relative Strength Index (RSI)**

Backtested on historical stock data of AAPL to evaluate trading signals and profitability.

#### 🛠️ Tech Stack:

* Python
* `pandas`, `numpy`, `matplotlib`,`backtrader`
* `yfinance` 
* Custom technical indicator functions 

#### 📈 Features:

* Buy/sell signal generation based on EMA/RSI crossovers
* Backtest framework with performance metrics:

  * Cumulative returns
  * Sharpe ratio
  * Drawdown analysis
* Visual overlays of indicators and trades

---

### 🛡️ 2. Credit Card Fraud Detection

#### 🧠 Description:

Built a highly accurate fraud detection system using:

* **Decision Tree Classifier**
* **XGBoost Classifier**

Dataset: [Kaggle Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

#### 🛠️ Tech Stack:

* Python
* `scikit-learn`, `xgboost`, `imbalanced-learn`
* `pandas`, `matplotlib`, `seaborn`,`numpy`

#### 🔍 Model Performance:

* ✅ **Accuracy:** **99%+**
* 🧾 **Classification Report:**

```
              precision    recall  f1-score   support

   Non-Fraud       1.00      1.00      1.00     56864
       Fraud       0.75      0.74      0.75        98

    accuracy                           1.00     56962
   macro avg       0.88      0.87      0.87     56962
weighted avg       1.00      1.00      1.00     56962
```

* 📉 **Imbalance Handling:** SMOTE (Synthetic Minority Oversampling Technique)
* 📊 **Model Comparison:** XGBoost outperformed Decision Tree in precision and AUC

#### 📈 Features:

* Full preprocessing pipeline (scaling, resampling)
* Confusion matrix and ROC curve plots
* Interpretability with feature importance

---


## 📬 Contact

**SAMYAK JAIN**
GMAIL - jsamyak2068@gmail.com

---
