# Hospital Length of Stay (LOS) Predictor 🏥📊

#### An end-to-end data science project utilizing Ordinary Least Squares (OLS) regression to predict patient Length of Stay (LOS) in hospitals based on clinical and demographic features.

## 📌 Project Overview
#### Accurate length-of-stay predictions are critical for hospital resource allocation, bed management, and patient flow optimization. This project evaluates how effectively standard clinical vitals, lab results, and demographic metrics can estimate total stay duration, while identifying key drivers and modeling constraints associated with long-stay outliers.

## 🔑 Key Results & Insights
#### **Model Fit** : Achieved an R^2 =0.76, explaining 76% of the variance in patient length of stay.

**Predictive Accuracy** : Maintained a Root Mean Squared Error (RMSE) of ~1.63 days on the test dataset.

**Feature Optimization** : Identified and removed statistically insignificant features (e.g., creatinine, bmi, pulse, sodium, glucose) using p-value thresholding without sacrificing overall model performance or explanatory power.

**Error Analysis** : High predictive precision across standard short stays (1–5 days), with expected linear regression underprediction observed on extreme long-stay outliers (>10 days).

🛠️ Tech Stack & Dependencies
**Language** : Python

**Data Manipulation** : pandas, NumPy

**Statistical Modeling & ML** : statsmodels, scikit-learn

**Data Visualization** : Seaborn, Matplotlib

Language & libraries
  - Language: Python
  - Data Manipulation: pandas, NumPy
  - Statistical Modeling & ML: statsmodels, scikit-learn
  - Statistical Modeling & ML: statsmodels, scikit-learn
  - 
**📊 Visualizations**
The project utilizes customized residual scatter plots with jittering and continuous color gradients to evaluate prediction errors:


**Residual Mapping:** Highlights overpredictions versus underpredictions along a diverging color scale (coolwarm), directly revealing variance patterns across target values.
1:1 Ideal Fit Alignment: Visualizes exact predictions versus real stay durations.
