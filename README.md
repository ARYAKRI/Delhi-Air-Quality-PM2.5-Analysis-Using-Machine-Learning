🌍 Delhi Air Quality Analysis and PM2.5 Prediction

Machine learning project for Delhi air quality analysis and PM2.5 prediction using XGBoost, time-series feature engineering, and SHAP explainability.

📌 Project Overview

This project focuses on analyzing and predicting PM2.5 air pollution levels in Delhi using historical air quality data from 2020–2023.

The project combines:

Data preprocessing

Exploratory Data Analysis (EDA)

Feature engineering

Machine Learning modeling

Explainable AI (SHAP analysis)

to understand pollution trends and forecast PM2.5 concentration levels.

🎯 Goals of the Project


## Objectives

- Analyze PM2.5 pollution trends in Delhi
- Understand AQI distribution and pollution severity
- Detect anomalies and outliers in AQI data
- Build a machine learning model for PM2.5 prediction
- Identify the most influential pollution-related features
- Improve interpretability using SHAP explainability analysis
- 
⚙️ What I did-

🔹 1. Data Collection & Preprocessing

- Collected Delhi air quality data from 2020–2023
- Cleaned missing and inconsistent values
- Performed feature engineering using lag variables
- Prepared time-series based input features


🔹 2. Exploratory Data Analysis (EDA)
Analyzed:

AQI distribution

Pollution trends

Outliers

Statistical behavior of PM2.5

Visualizations helped identify:

High pollution periods

Seasonal concentration patterns

Extreme AQI conditions

🔹 3. Feature Engineering
Created lag-based features such as:

pm2_5_lag1

pm10_lag1

no2_lag1

so2_lag1

hour

etc.

This improved time-series prediction performance.

🔹 4. Machine Learning Modeling

- Trained an XGBoost regression model
- Used historical pollutant values to predict PM2.5 concentration
- Evaluated model performance using observed vs predicted analysis
This is important because:
👉 You are not doing simple visualization only.
👉 This becomes a real ML forecasting project.

🔹 5. Explainable AI (SHAP Analysis)
Performed:

SHAP Feature Importance Analysis

SHAP Summary Visualization

to understand:

Which variables influence PM2.5 most

Positive and negative feature impacts

Model interpretability

📊 Results & Insights

## Results

- AQI values were highly skewed toward unhealthy pollution levels.
- Severe pollution spikes were observed during multiple periods.
- Lag-based PM2.5 features had the highest predictive importance.
- The XGBoost model successfully captured temporal PM2.5 patterns.
- SHAP analysis revealed that previous PM2.5 values strongly influenced future concentrations.
- The model predictions closely followed observed PM2.5 trends.


