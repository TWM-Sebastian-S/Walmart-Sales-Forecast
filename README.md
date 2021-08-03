# Predicting Walmart Sales - Tyme Series Analysis

### This is one of my personal DS/ML/DL projects I've been working in since I started my career as a Data Scientist.

## Project Overview

Machine Learning Project in Python created to forecast Walmart sales using statistical, ARIMA and Random Forest Regressors.
Project included: 
  - Breakdown Problem Statement
  - EDA & database cleaning
  - Perform Univariate & bi-variate analysis for both numeric and categorical variables
  - Feature engineering and feature selection
  - Prepare the data for modelling
  - Create models using:
    - Random Forest
    - Statistical Model
    - ARIMA (Autoregressive integrated moving average)
  - Perform Hyper-parameter tuning
  - Compare the performance of different models using RMSE.


## Problem Statement

One challenge of modeling retail data is the need to make decisions based on limited history. If Christmas comes but once a year, so does the chance to see how strategic decisions impacted the bottom line.

In this recruiting competition, job-seekers are provided with historical sales data for 45 Walmart stores located in different regions. Each store contains many departments, and participants must project the sales for each department in each store. To add to the challenge, selected holiday markdown events are included in the dataset. These markdowns are known to affect sales, but it is challenging to predict which departments are affected and the extent of the impact.


## Code and resources used
**Python Version:** 3.7

**Packages:** Pandas / Numpy / Seaborn / Scikitlearn / statsmodels / 

**ML Resources:** Logistic Regression / Gradient Boosting / Cross-validation / AUC / ROC / Confusion Matrix


## Model Building

- With an ARIMA model, you can forecast a time series using the series past values.
- If you use only the previous values of the time series to predict its future values, it is called Univariate Time Series Forecasting.
- If you use predictors other than the series (a.k.a exogenous variables) to forecast it is called Multi Variate Time Series Forecasting.
- ARIMA, short for ‘Auto Regressive Integrated Moving Average’ is actually a class of models that ‘explains’ a given time series based on its own past values, that is, its own     lags and the lagged forecast errors, so that equation can be used to forecast future values.

## Model Performance

I evaluated the performance of the models based on RMSE.

![Model Comparison](https://github.com/TWM-Sebastian-S/Walmart-Sales-Forecast/blob/main/Comparison%20of%20different%20models.JPG "Model Comparison")


## Conclusion



[GitHub Repository](https://github.com/TWM-Sebastian-S/Walmart-Sales-Forecast)
