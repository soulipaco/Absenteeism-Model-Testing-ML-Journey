# 📊 Department 2 - Absenteeism Model Testing

This folder contains the analysis and model testing specific to **Department 2**, which represents a **High-Level Headcount Project** with **750+ employees**. The analysis aims to predict absenteeism trends and improve workforce management through data-driven insights.

---

## 📒 Files Included
- **Notebook:** `Absenteeism Model Testing Department 2.ipynb`
- **Report:** `Absenteeism Model Testing Department 2.pdf`

---

## 🧪 Project Overview

The model testing process for Department 2 focuses on:
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
- **R² Score:** 0.6993  
- **MSE:** 11.8422  
- **MAE:** 1.5421  
- **RMSE:** 3.4412  
- ⏱️ *Training Time:* 12.34 seconds  

### ✅ **XGBoost:**  
- **R² Score:** 0.6454  
- **MSE:** 13.9649  
- **MAE:** 1.6139  
- **RMSE:** 3.7370  
- ⏱️ *Training Time:* 0.27 seconds  

### ✅ **LightGBM:**  
- **R² Score:** 0.6576  
- **MSE:** 13.4856  
- **MAE:** 1.6544  
- **RMSE:** 3.6723  
- ⏱️ *Training Time:* 0.85 seconds  

### ✅ **Ridge Regression:**  
- **R² Score:** 0.4704  
- **MSE:** 20.8573  
- **MAE:** 2.2474  
- **RMSE:** 4.5670  
- ⏱️ *Training Time:* 0.07 seconds  

### ✅ **Linear Regression:**  
- **R² Score:** 0.5699  
- **MSE:** 16.9382  
- **MAE:** 2.1050  
- **RMSE:** 4.1156  
- ⏱️ *Training Time:* 0.20 seconds  

> The analysis provided critical insights into absenteeism patterns, enabling better workforce planning and resource allocation.

---

## 🚀 Next Steps

- Apply the model to new data for real-world validation.
- Compare with Department 1 results for consistency.
- Integrate findings into predictive dashboards for continuous monitoring.

---

**For detailed code and analysis, refer to the Jupyter notebook and PDF report included in this folder.**

