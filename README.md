# Customer Churn Prediction

A machine learning classification project to predict customer churn using behavioral and demographic features from telecom data. Built with Python, scikit-learn, and Jupyter Notebook.

---

## 📊 Results

| Metric | No Churn (0) | Churn (1) | Overall |
|--------|-------------|-----------|---------|
| Precision | 0.83 | 0.65 | — |
| Recall | 0.88 | 0.56 | — |
| F1 Score | 0.85 | 0.60 | — |
| **Accuracy** | — | — | **78%** |

> **Key finding:** The model identifies non-churners with high precision (83%) but churn detection (65%) reveals class imbalance — a common challenge in real-world churn datasets where churners are the minority class.

---

## 🎯 Objective

Build and evaluate a binary classification model that predicts whether a telecom customer is likely to churn, enabling proactive retention strategies.

---

## 📂 Dataset

- **Source:** `customer_churn.csv`
- **Size:** 1,407 test samples (0: 999 no churn, 1: 408 churn)
- **Features:** Gender, contract type, tenure, monthly charges, internet service, payment method, and more
- **Target:** `Churn` (Yes/No → 1/0)

---

## 🔧 Tech Stack

- **Language:** Python 3
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Environment:** Jupyter Notebook / Google Colab

---

## 🚀 Workflow

1. **Data Cleaning** — Handle missing values, fix data types
2. **Exploratory Data Analysis (EDA)** — Distribution plots, correlation heatmaps, churn rate by feature
3. **Feature Engineering** — Label encoding, one-hot encoding, feature scaling
4. **Model Training** — Classification algorithms with train/test split
5. **Evaluation** — Accuracy, Precision, Recall, F1 Score, Confusion Matrix

---

## 📈 Key Insights from EDA

- Customers on **month-to-month contracts** churn significantly more than annual contract holders
- **Higher monthly charges** correlate strongly with churn
- **Tenure** is inversely correlated with churn — longer customers are more loyal
- Customers using **fiber optic internet** show higher churn rates

---

## ⚠️ Class Imbalance Note

The dataset is imbalanced (churners ~29% of data). Future improvements:
- SMOTE oversampling
- Class weight adjustment
- Ensemble methods (Random Forest, XGBoost)

---

## 📁 Files

| File | Description |
|------|-------------|
| `churn.ipynb` | Full notebook with EDA, preprocessing, modeling, and evaluation |
| `customer_churn.csv` | Dataset |

---

## ▶️ How to Run

```bash
git clone https://github.com/yukta31/customer-churn-prediction.git
cd customer-churn-prediction
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook churn.ipynb
```

Or open directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/115E1s5GJkDxHWczdPWO1Zhube-cfqzjQ)

---

## 👩‍💻 Author

**Yukta Batra** — MS Computer Science, George Mason University

[Portfolio](https://yukta-batra.vercel.app) · [LinkedIn](https://linkedin.com/in/yuktabatra31) · [GitHub](https://github.com/yukta31)
