# Telco Customer Churn Prediction (AI/ML Assessment)

## Overview
This project is an AI/ML internship assessment focused on predicting customer churn using the Telco Customer Churn dataset. The goal is to demonstrate practical skills in data analysis, exploratory data analysis (EDA), machine learning model building, evaluation, and basic deployment readiness.

The project follows a real-world machine learning workflow and is implemented using Python in a Jupyter Notebook.

---

## Dataset
- **Name:** Telco Customer Churn Dataset  
- **Source:** https://www.kaggle.com/blastchar/telco-customer-churn  
- **Target Variable:** `Churn`  
  - `1` → Customer churned  
  - `0` → Customer retained  

---

## Project Workflow

### 1. Data Cleaning & Exploratory Data Analysis (EDA)
- Loaded and explored the dataset (shape, data types, missing values)
- Handled inconsistent data (`TotalCharges` converted to numeric)
- Generated descriptive statistics and correlation analysis
- Created meaningful visualizations:
  - Churn by contract type
  - Distribution of customer tenure
- Derived key business insights from the data

### 2. Model Building & Evaluation
- Defined target variable (`Churn`) and selected features
- Split data into training and testing sets
- Trained multiple machine learning models:
  - Logistic Regression
  - Random Forest Classifier
- Evaluated models using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - ROC-AUC (bonus)
- Compared model performance and selected the best model

### 3. Bonus & Deployment Readiness
- Hyperparameter tuning for Random Forest
- Feature importance analysis
- Saved the trained model using `joblib` for future use or deployment

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

## Files in Repository
- `assessment.ipynb` – Complete Jupyter Notebook with analysis and models
- `customer_churn_model.pkl` – Saved trained model
- `README.md` – Project documentation

---

## Key Insights
- Customers with month-to-month contracts have the highest churn rate
- Short-tenure customers are more likely to churn
- Higher monthly charges increase churn probability

---

## Conclusion
This project demonstrates the ability to handle real-world data, extract insights, build and evaluate machine learning models, and apply best practices for model persistence. It is suitable as an internship-level AI/ML project and can be extended for deployment in production systems.

---

## Author
Priyanshu Shukla
