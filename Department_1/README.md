# 📊 Department 1 - Absenteeism Model Testing

This folder contains the analysis and model testing specific to **Department 1**, which represents a **Mid-Level Headcount Project** with **250–300 employees**. The analysis aims to predict absenteeism trends and improve workforce management through data-driven insights.

---

## 📒 Files Included
- **Notebook:** `Absenteeism Model Testing Department 1.ipynb`
- **Report:** `Absenteeism Model Testing Department 1.pdf`

---

## 🧪 Project Overview

The model testing process for Department 1 focuses on:
- **Data Preprocessing:** Cleaning, handling missing values, and data normalization.
- **Exploratory Data Analysis (EDA):** Uncovering patterns and trends.
- **Feature Selection:** Using Recursive Feature Elimination with Cross-Validation (RFECV).
- **Hyperparameter Tuning:** Optimization via RandomizedSearchCV.
- **Model Evaluation:** Utilizing key performance metrics for accuracy assessment.

---

## 🔑 Key Highlights

- **Data Preprocessing:** Handling missing values, outliers, and data normalization.
- **Feature Engineering:** Creation of lag and rolling features to capture temporal patterns.
- **Feature Selection:** Implementing RFECV to identify the most predictive features.
- **Model Training:** Testing models like Random Forest, XGBoost, and LightGBM.
- **Hyperparameter Tuning:** Optimization using RandomizedSearchCV for performance enhancement.
- **Model Evaluation:** Metrics such as **R²**, **MAE**, **MSE**, and **RMSE** to assess model accuracy.

---

## 📈 Results Summary

### ✅ **Random Forest:**  
- **R² Score:** 0.5624  
- **MSE:** 12.8404  
- **MAE:** 1.8248  
- **RMSE:** 3.5833  
- ⏱️ *Training Time:* 0.50 seconds  

### ✅ **XGBoost:**  
- **R² Score:** 0.5597  
- **MSE:** 12.9173  
- **MAE:** 1.8215  
- **RMSE:** 3.5941  
- ⏱️ *Training Time:* 0.13 seconds  

### ✅ **LightGBM:**  
- **R² Score:** 0.4252  
- **MSE:** 16.8644  
- **MAE:** 2.0270  
- **RMSE:** 4.1066  
- ⏱️ *Training Time:* 0.03 seconds  

### ✅ **Ridge Regression:**  
- **R² Score:** 0.4628  
- **MSE:** 15.7607  
- **MAE:** 2.3224  
- **RMSE:** 3.9700  
- ⏱️ *Training Time:* 0.01 seconds  

### ✅ **Linear Regression:**  
- **R² Score:** 0.4459  
- **MSE:** 16.2574  
- **MAE:** 2.3618  
- **RMSE:** 4.0320  
- ⏱️ *Training Time:* 0.01 seconds  

> The analysis provided critical insights into absenteeism patterns, enabling better workforce planning and resource allocation.

---

## 🚀 Next Steps

- Apply the model to new data for real-world validation.
- Compare with Department 2 results for consistency.
- Integrate findings into predictive dashboards for continuous monitoring.

---

**For detailed code and analysis, refer to the Jupyter notebook and PDF report included in this folder.**
