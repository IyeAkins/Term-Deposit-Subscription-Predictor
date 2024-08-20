# Term-Deposit-Subscription-Predictor
Predict customer subscriptions to a bank's term deposit using an XGBoost model

This repository contains code that uses an XGBoost model to predict whether customers will subscribe to a term deposit during a bank's marketing campaign. The model is built using customer data, which is explored and visualized through various exploratory data analysis (EDA) techniques before training the model.
Features

Data Exploration and Visualization: The code includes various plots to understand the distribution of data and the relationship between features and the target variable.
Model Training: The code trains an XGBoost classifier with hyperparameter tuning using GridSearchCV.
Performance Evaluation: The model's performance is evaluated using confusion matrices, classification reports, and feature importance plots.
SHAP Analysis: SHAP values are used to interpret the impact of features on the model's predictions.
Installation

To run this code, you will need to have the following libraries installed:

pip install pandas seaborn matplotlib xgboost shap scikit-learn

Usage
Load Data: The dataset is loaded from bank-full.csv, which should be in the same directory as the script.
Exploratory Data Analysis (EDA): Visualize the distribution of features and their relationship with the target variable (y).
Model Training and Hyperparameter Tuning: Train the XGBoost model and tune its hyperparameters using cross-validation.
Model Evaluation: Evaluate the model's performance and interpret the results using confusion matrices, classification reports, and SHAP plots.
Conclusion

This project aims to predict customer behavior during a bank marketing campaign, focusing on whether a customer will subscribe to a term deposit. The use of EDA and SHAP values helps in understanding the factors that influence customer decisions.

