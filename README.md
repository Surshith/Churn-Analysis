# Churn-Analysis

# Customer Churn Prediction Using Machine Learning

## 📌 Project Overview
This project focuses on predicting whether a customer will churn (leave the service) using historical customer data. Customer churn prediction helps businesses proactively identify high-risk customers and take retention actions.

The project applies machine learning techniques to classify customers into churn and non-churn categories based on demographic, service usage, and billing information.

---

## 🛠️ Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- SMOTE (Imbalanced-learn)
- Random Forest, Decision Tree, XGBoost
- Pickle

---

## 📂 Dataset
- **Source:** Telco Customer Churn Dataset
- **Target Variable:** `Churn` (Yes / No)
- **Features:** Customer demographics, services, contract type, and billing details

---

## 🔄 Project Workflow
1. Data loading and inspection
2. Data cleaning and preprocessing
3. Exploratory Data Analysis (EDA)
4. Encoding categorical variables
5. Handling class imbalance using SMOTE
6. Train-test split
7. Model training and evaluation
8. Model comparison

---

## 📊 Models Used
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Random Forest Classifier

---

## 📈 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Special emphasis was placed on **recall for churn customers**, as identifying churn-prone customers is critical for business retention.

---

## ✅ Key Outcomes
- Successfully built a binary classification model to predict customer churn
- Ensemble models showed improved performance over a single decision tree
- Demonstrated a complete end-to-end machine learning workflow

---

## 🔮 Future Enhancements
- Feature importance and explainability (SHAP)
- Churn probability prediction
- Model deployment using Streamlit or Flask
