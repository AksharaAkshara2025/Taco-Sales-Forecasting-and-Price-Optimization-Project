**Taco Sales Forecasting & Price Optimization (2024–2025)**

**Project Overview**
This project analyzes and forecasts taco sales using the Taco Sales Dataset (2024–2025) available on Kaggle.
The dataset provides recent sales transactions for a fictional taco restaurant chain, enabling advanced time series forecasting, price optimization, and interactive business insights.

The main objective is to build an end-to-end forecasting and analytics solution to help optimize:
Inventory planning
Pricing strategies
Promotional decisions

Dataset Link: https://www.kaggle.com/datasets/atharvasoundankar/taco-sales-dataset-20242025  

**Objectives**

Data Ingestion & Cleaning

Load and explore the dataset using Python (pandas, numpy).

Handle missing values, detect anomalies, and identify seasonal patterns.

Exploratory Data Analysis (EDA)

Visualize trends in sales volume, revenue, and pricing.

Identify seasonal effects, day-of-week patterns, and price correlations using matplotlib and seaborn.

Time Series Forecasting

Implement multiple forecasting models:
Traditional: ARIMA, SARIMA, Exponential Smoothing
Machine Learning: Random Forest, Gradient Boosting
Advanced: Prophet, LSTM Neural Network

Evaluate model accuracy using MAE, RMSE, and MAPE metrics.

**Price Optimization**

Train ML models (e.g., Random Forest, XGBoost) to predict optimal pricing points that maximize revenue or sales.
Include key business variables such as day of week, seasonality, and promotions.

**Interactive Dashboard**

Develop a Power BI Dashboard 
Display:
Forecasted and historical sales
Revenue and pricing trends
KPI insights: projected revenue, stock needs, price elasticity

**Tech Stack**

Phase	Tools & Libraries
Data Processing -	Python (pandas, numpy)
Visualization -	matplotlib, seaborn
Forecasting Models - ARIMA, SARIMA, Prophet, LSTM
Machine Learning - Random Forest, XGBoost
Dashboard -	Power BI / Tableau
Evaluation -	MAE, RMSE, Accuracy metrics

**Results and Outcomes**

**Top Performing Model:**
SARIMA and Prophet provided the most consistent forecasts with the lowest RMSE.

**Forecast Accuracy:**
Achieved an RMSE reduction of ~18% after hyperparameter tuning and feature engineering.

**Price Optimization Insights:**
The Random Forest model identified that moderate price adjustments (±5%) during peak days (weekends and holidays) significantly increase revenue.

**Seasonality Findings:**
Sales peak during weekends and festive months (December–February).
Rainy days and mid-week periods show slightly reduced sales.

**Business Dashboard:**
The Power BI dashboard integrates sales forecasts and pricing simulations, enabling decision-makers to visualize:
Upcoming weekly/monthly sales forecasts
Revenue trends
Optimal pricing recommendations
Inventory and stock planning metrics

**Key Learnings**

End-to-end analytics workflow integrating data cleaning → forecasting → optimization → dashboarding.
Demonstrates practical use of time series + ML models for real-world decision-making.

Builds proficiency with Python, ML, and BI tools for applied business analytics.
