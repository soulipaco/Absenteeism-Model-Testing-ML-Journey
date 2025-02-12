# 📊 Absenteeism Model Testing ML Journey

Welcome to the **Absenteeism Model Testing** repository. This project focuses on rigorous model evaluation, feature selection, and hyperparameter tuning to predict absenteeism trends using machine learning algorithms.

## 🚀 Repository Structure

Absenteeism-Model-Testing-ML-Journey/
├── Department_1/
│   ├── Absenteeism Model Testing Department 1.ipynb
│   └── Absenteeism Model Testing Department 1.pdf
├── Department_2/
│   ├── Absenteeism Model Testing Department 2.ipynb
│   └── Absenteeism Model Testing Department 2.pdf
└── Final_Stage/
    ├── Absenteeism Model Testing Final Stage.ipynb
    └── Absenteeism Model Testing Final Stage.pdf

🧪 Project Overview
This repository showcases the Model Testing Phase of the absenteeism project, focusing on model performance across varying workforce sizes:

Department 1: Analysis for a Mid-Level Headcount Project with 250–300 employees.
Department 2: Analysis for a High-Level Headcount Project with 750+ employees.
Final Stage: Combined data evaluation to test model generalization across both departments.
Note: Department 1 and Department 2 follow identical methodologies, differing only in the datasets used. The goal is to test model adaptability to different project scales.

⚡ Tech Stack
Languages & Tools: Python, SQL Server (for data preparation)
Libraries:
pandas, NumPy for data manipulation
scikit-learn for model training and evaluation
XGBoost, LightGBM for advanced machine learning models
Matplotlib, Seaborn for data visualization
Machine Learning Models:
Random Forest for robust, non-linear relationships
XGBoost for optimized gradient boosting
LightGBM for efficient large-scale datasets
Feature Engineering:
Rolling and lagged metrics
Derived statistical features
Handling data skewness through log transformations
📈 Key Analyses
Data Preparation: Time-based aggregations, handling missing values, and skewness reduction.
Feature Engineering: Creation of lag and rolling window features to capture temporal dependencies.
Model Testing: Evaluating multiple models with RFECV and hyperparameter tuning.
Final Stage: Combined testing to ensure the models generalize well across departments.
🔍 Next Steps
Stay tuned for upcoming predictive models based on these analyses, focusing on improving scalability and generalizability in workforce management. 🚀
