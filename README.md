# Bike Sharing Predictive Analysis
## Overview
This project focuses on predicting bike-sharing demand using machine learning models. The dataset includes features like time, weather, and seasonal data to enhance operational efficiency and user satisfaction.

## Key Features
**Preprocessing:**
* Categorical features (Humidity_Binned) encoded using One-Hot Encoding.
* Numerical features standardized with Standard Scaler.
* Dataset split into 70% training and 30% testing data.

**Feature Engineering:**
* dteday split into Year, Month, and Day.
* Humidity categorized into Low, Medium, and High.
* Removed redundant columns.

**Modeling:**
* Evaluated multiple regression models, including Random Forest and XGBoost.
* XGBoost and Random Forest showed the best performance with RMSE ≈ 86.

**Feature Importance:**
* Key features: Hour, Year, and Temperature.
* SHAP analysis used to interpret model predictions.

## Usage
* Run the notebook to preprocess data and train models.
* Evaluate model performance using RMSE, MAE, and R² metrics.
* Use SHAP plots for feature importance insights.

## Results
* Best Models: XGBoost and Random Forest.
* Insights: Time of day, temperature, and year significantly impact bike demand.

## Requirements
* Python 3.12+
* Libraries: scikit-learn, XGBoost, pandas, numpy, matplotlib, SHAP.

*This project provides actionable insights to optimize bike-sharing operations.*
