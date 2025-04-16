# 🚗 Motor Insurance Premium Prediction


## Dataset
https://www.kaggle.com/datasets/ifteshanajnin/carinsuranceclaimprediction-classification

This project aims to build a predictive model for motor insurance premium pricing using various policyholder and vehicle-related features. The goal is to support insurance companies in setting fair, accurate, and data-driven premiums.

## 📌 Project Overview

Insurance pricing is traditionally based on underwriting experience and historical data. This project takes a machine learning approach to develop a regression model that predicts insurance premiums using key customer and vehicle information.

The dataset includes features like:
- **MVR_PTS** – Motor Vehicle Record points
- **Revoked_yes** – License Revocation status
- **CAR_USE_Private** – Car use type
- **CAR_AGE** – Age of the car
- **OLDCLAIM** – Previous claim amount
- **CLAIM_FLAG** – Indicates if a claim was made
- **CLAIM_FREQ** – Frequency of claims

## 🔍 Problem Statement

The objective is to **accurately predict motor insurance premiums** based on input variables, improving upon traditional actuarial methods by applying machine learning models.

## 📊 Dataset

The dataset used is anonymized and preprocessed. Key preprocessing steps include:
- Handling missing values
- Encoding categorical variables
- Feature scaling and transformation
- Train-test split for model validation

## 🧠 Models Used

Several machine learning models were evaluated:
- **Linear Regression**
- **Ridge and Lasso Regression**
- **Random Forest Regressor**
- **XGBoost Regressor**

## 📈 Evaluation Metrics

The following metrics were used to evaluate model performance:
- **R-squared (R²) Score**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **Mean Absolute Error (MAE)**

## 📦 Tools & Technologies

- Python
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn
- XGBoost

## 🧾 Future Work

- Incorporate additional features like driver demographics
- Explore deep learning models
- Apply interpretability techniques like SHAP for feature importance
