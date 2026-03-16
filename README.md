# DevelopersHub AI/ML Engineering Internship Tasks

## Task 2: End-to-End ML Pipeline for Customer Churn Prediction

### Task Objective

Learn how to build a reusable and production-ready machine learning pipeline using Scikit-learn to predict whether a telecom customer will churn.

### Dataset Used

Source: IBM Telco Customer Churn Dataset

Features Used: Customer demographics, service subscriptions, tenure, contract type, payment method, monthly charges, total charges

Target Variable: Churn (Yes / No)

### Models Applied

Logistic Regression
Random Forest Classifier

### Key Results and Findings

The Telco Customer Churn dataset was successfully loaded and preprocessed.
Data preprocessing steps such as handling missing values, scaling numerical features, and encoding categorical variables were implemented using Scikit-learn pipelines.
Both Logistic Regression and Random Forest models were trained using the pipeline.
GridSearchCV was used to perform hyperparameter tuning and select the best model.
Random Forest generally performed better due to its ability to capture complex relationships between features.
The final pipeline was exported using joblib, making it reusable for future predictions.

### Notebook

Notebook: https://colab.research.google.com/drive/10zaaogrCSft51Y4gl3y-gZ6aKuidGDAX?usp=sharing
