# 🏨 Hotel Booking Cancellation Prediction

## 📌 Project Overview
This project focuses on predicting whether a hotel booking will be **cancelled or not** using machine learning techniques.  
Accurate cancellation prediction helps hotels improve revenue management and operational planning.

---

## 🎯 Problem Statement
Given historical hotel booking data, predict if a booking will be cancelled (`1`) or not (`0`).

---

## 📊 Dataset Details
- Dataset contains **30,000+ booking records**
- Target column: `is_canceled`
- Key features:
  - Hotel type
  - Lead time
  - Arrival month
  - Meal plan
  - Deposit type
  - Booking changes
  - Customer behavior attributes

---

## 🛠️ Technologies Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- XGBoost  
- Matplotlib, Seaborn  
- Joblib  
- Streamlit  

---

## ⚙️ Project Workflow
1. Data cleaning and preprocessing  
2. Feature encoding  
3. Train-test split  
4. Handling class imbalance  
5. Model training  
6. Model evaluation  
7. Hyperparameter tuning  
8. Best model selection  
9. Model deployment using Streamlit  

---

## 🤖 Models Implemented
- Logistic Regression  
- Random Forest  
- Gradient Boosting  
- XGBoost  

Hyperparameter tuning was performed using **RandomizedSearchCV**.

---

## 🏆 Final Model Performance (XGBoost)
- Train Accuracy: **81%**
- Test Accuracy: **81%**
- ROC-AUC Score: **0.86**
- Precision: **0.83**
- Recall: **0.62**

XGBoost was chosen as the final model based on overall performance.
---
---

