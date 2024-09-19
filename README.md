# Churn-Prediction
Overview
This FastAPI application provides an interface for predicting customer churn and explaining predictions using various machine learning models. The API allows users to submit feature data and receive predictions along with probabilistic scores. It also offers explanations of predictions using LIME and SHAP techniques.

Features
Predict Churn: Use trained models to predict whether a customer will churn.
Explain Predictions: Get explanations for predictions using LIME and SHAP.
Support for Multiple Models: Choose from multiple machine learning models for predictions.
Models
The following machine learning models are supported:

Random Forest (rf_model)
Logistic Regression (lr_model)
XGBoost (xgb_model)
Setup
Prerequisites
Ensure you have Python 3.7 or later installed. You will also need the following libraries:

FastAPI
Uvicorn
Pyngrok
Scikit-learn
XGBoost
LIME
SHAP
Pandas
