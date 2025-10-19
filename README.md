# 🧠 Customer Churn Prediction (Telecom)

An end-to-end Machine Learning project that predicts whether a telecom customer is likely to churn in the next month using demographic, account, and service data.

## 🚀 Project Overview
- **Goal:** Identify customers at risk of churn to enable proactive retention.
- **Dataset:** [Telco Customer Churn Dataset (Kaggle)](https://www.kaggle.com/blastchar/telco-customer-churn)
- **Tech Stack:** Python, Pandas, Scikit-learn, XGBoost, SHAP, Matplotlib, Seaborn

## 🧩 Workflow
1. **Data Preprocessing:** Handled missing values, encoded categorical variables, and scaled features.
2. **EDA:** Visualized churn trends across contract type, tenure, and payment method.
3. **Modeling:** Trained Logistic Regression, Random Forest, and XGBoost.
4. **Evaluation:** Used ROC-AUC, F1-score, and Confusion Matrix for performance analysis.
5. **Explainability:** Applied SHAP to interpret key churn drivers.
6. **Business Insights:** Recommended retention actions based on model findings.

## 📊 Results
- **Best Model:** XGBoost with ROC-AUC = 0.88
- **Top Features:** Contract Type, Tenure, Monthly Charges

## 🧰 Installation
```bash
pip install -r requirements.txt
