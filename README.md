# ChurnShield - Customer Churn Prediction Dashboard

## Project Overview

Customer churn is one of the biggest challenges faced by telecom companies. This project analyzes customer behavior using the IBM Telco Customer Churn dataset to identify factors influencing customer churn and build machine learning models capable of predicting whether a customer is likely to leave the service.

The project follows a complete Data Science workflow including data preprocessing, exploratory data analysis, feature engineering, model training, model evaluation, hyperparameter tuning, explainability, and deployment through an interactive Streamlit dashboard.

---

## Objectives

- Analyze telecom customer data
- Identify key churn drivers
- Perform data preprocessing and feature engineering
- Train multiple machine learning models
- Compare model performance
- Optimize the best-performing model
- Explain predictions using SHAP
- Deploy an interactive Streamlit dashboard

---

## Dataset

**Dataset:** IBM Telco Customer Churn Dataset

The dataset contains demographic information, subscribed telecom services, billing information, account details, and customer churn status.

### Dataset Summary

- Total Records: **7,043**
- Original Features: **50**
- Final Training Features: **43**
- Target Variable: **Churn Label**
- File Format: **CSV**

**Dataset Source:**  
https://www.kaggle.com/datasets/blastchar/telco-customer-churn

---

## Tech Stack

### Programming Language

- Python

### Data Processing

- Pandas
- NumPy

### Data Visualization

- Matplotlib
- Seaborn
- Plotly

### Machine Learning

- Scikit-Learn
- XGBoost

### Explainability

- SHAP

### Dashboard

- Streamlit

### Model Persistence

- Joblib

---

## Machine Learning Models

The following machine learning models have been implemented:

- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier

---

## Model Evaluation

Models are evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix
- ROC Curve
- Precision-Recall Curve
- 5-Fold Cross Validation
- Hyperparameter Tuning using GridSearchCV

---

## Features

- Dataset inspection
- Missing value analysis
- Duplicate detection
- Data cleaning
- Exploratory Data Analysis (EDA)
- One-Hot Encoding
- Label Encoding
- StandardScaler normalization
- Feature Engineering
- Feature Selection
- Machine Learning Pipelines
- Logistic Regression
- Random Forest
- XGBoost
- Cross Validation
- Hyperparameter Optimization
- Model Performance Comparison
- Interactive Streamlit Dashboard (In Progress)

---

## Project Structure

```text
ChurnShield-Customer-Churn-Prediction-Dashboard/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_Data_Inspection.ipynb
│   ├── 02_EDA.ipynb
│   ├── 03_Feature_Engineering.ipynb
│   └── 04_Model_Training.ipynb
│
├── models/
├── reports/
├── images/
├── src/
│
├── app.py
├── requirements.txt
├── README.md
└── .gitignore
```

---

## Project Workflow

### Completed

- Dataset inspection
- Data cleaning
- Exploratory Data Analysis
- Feature Engineering
- Data preprocessing
- One-Hot Encoding
- StandardScaler
- Feature Selection
- Train-Test Split
- Logistic Regression training
- Random Forest training
- XGBoost training
- Cross Validation
- Model Evaluation
- Hyperparameter Tuning using GridSearchCV

### Upcoming

- SHAP Explainability
- Model Saving using Joblib
- Streamlit Dashboard Development
- Business Insights Report
- Dashboard Deployment

---

## Current Progress

- ✅ Dataset Inspection
- ✅ Data Cleaning
- ✅ Exploratory Data Analysis
- ✅ Feature Engineering
- ✅ Model Training
- ✅ Model Evaluation
- ✅ Hyperparameter Tuning
- ⏳ SHAP Explainability
- ⏳ Model Persistence
- ⏳ Streamlit Dashboard
- ⏳ Final Insights Report

---

## How to Run

Clone the repository

```bash
git clone https://github.com/nidhi-yadav20799/ChurnShield-Customer-Churn-Prediction-Dashboard.git
```

Move into the project folder

```bash
cd ChurnShield-Customer-Churn-Prediction-Dashboard
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the Streamlit application

```bash
streamlit run app.py
```

---

## Future Improvements

- Generate SHAP feature importance visualizations
- Save the trained model using Joblib
- Build an interactive Streamlit dashboard
- Deploy the application online
- Add detailed business insights and recommendations

---

## References

- IBM Telco Customer Churn Dataset
- Scikit-Learn Documentation
- XGBoost Documentation
- SHAP Documentation
- Streamlit Documentation

---

## Author

**Nidhi Yadav**


GitHub: https://github.com/nidhi-yadav20799