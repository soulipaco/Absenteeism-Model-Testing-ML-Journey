# 📊 Final Stage - Absenteeism Model Testing

This folder contains the **final combined model evaluation**, leveraging insights from **Department 1** and **Department 2**. The goal is to optimize absenteeism prediction models for robust, scalable performance across dynamic operational environments.

---

## 📒 Files Included
- **Notebook:** `Absenteeism Model Testing Final Stage.ipynb`
- **Report:** `Absenteeism Model Testing Final Stage.pdf`

---

## 🧪 Project Overview

The **Final Stage** integrates data and insights from previous analyses to:
- Combine datasets from **Department 1** and **Department 2** for holistic testing.
- Evaluate models to ensure **scalability** and **generalization**.
- Optimize models for **incremental learning** and potential **reinforcement learning** applications.

---

## 🔑 Key Highlights

1. **Combined Data Analysis:**  
   Merging data from both departments to test generalization across diverse datasets.

2. **Model Selection Strategy:**  
   - **Eliminated Models:**  
     ❌ **Linear Regression** and **Ridge Regression** due to heavy dependence on categorical features and limited adaptability.  
     ❌ **LightGBM** due to over-reliance on `MU_Name` features, affecting generalization.
   - **Selected Models:**  
     ✅ **Random Forest** and ✅ **XGBoost** for their robustness and minimal dependence on categorical features.  
     ✅ **Voting Regressor** (combining Random Forest & XGBoost) for enhanced predictive power.

3. **Feature Engineering:**  
   - Focus on **rolling and lagged features** to capture temporal patterns.  
   - Utilization of **Department 2's best hyperparameters** for combined testing.

4. **Advanced Techniques:**  
   Exploration of **Voting Regressor** for ensemble learning, combining the strengths of multiple models.

---

## 📈 Model Performance Summary

### 🚀 **1️⃣ Combined Features Performance**

| Model               | R²     | MSE      | MAE     | RMSE    | Training Time (s) |
|---------------------|--------|----------|---------|---------|-------------------|
| **RandomForest**    | 0.5859 | 15.4467  | 1.6384  | 3.9302  | 15.81             |
| **XGBoost**         | 0.6110 | 14.5137  | 1.6578  | 3.8097  | 0.20              |
| **Voting Regressor**| 0.6874 | 11.6607  | 1.5981  | 3.4148  | 22.89             |

### 🚀 **2️⃣ Department 2 Features Performance**

| Model               | R²     | MSE      | MAE     | RMSE    | Training Time (s) |
|---------------------|--------|----------|---------|---------|-------------------|
| **RandomForest**    | 0.6822 | 11.8561  | 1.5852  | 3.4433  | 15.22             |
| **XGBoost**         | 0.6351 | 13.6144  | 1.6621  | 3.6898  | 0.25              |
| **Voting Regressor**| 0.6807 | 11.9102  | 1.6066  | 3.4511  | 16.35             |

---

## 🎯 **Key Insights**

- **🏆 Best Model:** **Voting Regressor (Combined Features)** with the **highest R² (0.6874)** and **lowest RMSE (3.4148)**.  
- **RandomForest** excels with **Department 2 Features**, showing strong generalization capacity.  
- **XGBoost** performs well but has slightly lower generalization compared to RandomForest.  
- **Department 2’s hyperparameters** enhance model performance when applied to combined data.

---

## ✅ **SHAP Analysis - Model Explainability**

### 🔍 **Key Findings:**
- **Top Influential Feature:** `Rolling_Last_7_Days_Total_Lost_Hours`—a critical predictor for absenteeism.  
- **Other Significant Features:**  
  - `Rolling_Last_7_Days_Absence_Hours`  
  - `Rolling_Last_7_Days_TotalLost_HC`  
  - `Strike_Participant%` shows high impact during strike periods.

### 📊 **SHAP Summary Insights:**
- **Positive SHAP Values:** High recent absenteeism and strike rates increase predicted absenteeism.  
- **Negative SHAP Values:** Stable schedules and low absenteeism trends reduce absenteeism predictions.

---

## 🚀 Next Steps

- Deploy the **Voting Regressor** in production environments for real-time absenteeism forecasting.  
- Explore **Incremental Learning** techniques to adapt the model to new data dynamically.  
- Conduct **Reinforcement Learning** experiments to optimize workforce scheduling based on predictive insights.  
- Integrate SHAP-driven insights into dashboards for **real-time model interpretability**.

---

**For detailed code and analysis, refer to the Jupyter notebook and PDF report included in this folder.**

