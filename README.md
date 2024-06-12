# Air_Quality-_Time_series_analysis_using_AutoReg_Model

## Project Overview
This project involves analyzing air quality data in Nairobi using various time series modeling techniques. We aim to predict future air quality measurements by building and evaluating multiple models, including Linear Regression, AutoReg (Autoregressive) models, and ARMA (AutoRegressive Moving Average) models. The models are evaluated based on their performance in terms of baseline and test mean absolute error (MAE).

## Models Implemented
1. Linear Regression with Time Series Data
Description: This model uses linear regression to predict air quality based on time series data. The approach involves fitting a linear model to the time series data and assessing its performance.

## Libraries Used:

pytz
pandas
matplotlib
plotly.express
pymongo
sklearn.linear_model.LinearRegression
sklearn.metrics.mean_absolute_error
Performance:

Baseline MAE: 7.2
Test MAE: 4.44

## 2. Autoregressive (AutoReg) Models on the Nairobi Air Quality Dataset
Description: This model uses the AutoReg algorithm to predict future values based on past observations. It is specifically designed for time series data where observations are dependent on their previous values.

## Libraries Used:
pandas
matplotlib
plotly.express
pymongo
sklearn.metrics.mean_absolute_error
statsmodels.graphics.tsaplots
statsmodels.tsa.ar_model.AutoReg
Performance:

Baseline MAE: 7.82
Test MAE: 4.13

## ARMA (Auto Regression Moving Average) Models for The Nairobi Air Quality Data
Description: This model combines both autoregression and moving average components to predict air quality. It captures dependencies between observations and errors in the time series data.

## Libraries Used:
time
warnings
pandas
matplotlib
plotly.express
seaborn
pymongo
sklearn.metrics.mean_absolute_error
statsmodels.graphics.tsaplots
statsmodels.tsa.arima.model.ARIMA
Performance:

Baseline MAE: 7.86
Test MAE: 3.56
Data Source
The air quality data for Nairobi was sourced from a reliable database and cleaned for analysis. The data includes various measurements that reflect the air quality over time.

## Methodology
Data Collection: Retrieved air quality data from the database.
Data Preprocessing: Cleaned and prepared the data for analysis.
Model Building:
Implemented Linear Regression to establish a baseline model.
Developed AutoReg models to capture temporal dependencies.
Created ARMA models to incorporate both autoregressive and moving average aspects.
Model Evaluation: Assessed models based on MAE, comparing baseline and test results.
Visualization: Used matplotlib and plotly for visualizing the data and model predictions.

## Results
The Linear Regression model provided a quick baseline with moderate performance.
The AutoReg model showed an improvement over the Linear Regression model, indicating that past values are significant predictors.
The ARMA model achieved the best performance, suggesting that combining autoregression and moving average elements effectively captures the complexities in the air quality data.

## Conclusion
This project demonstrates the application of time series modeling techniques to predict air quality in Nairobi. The ARMA model was the most effective, providing the lowest test MAE. These models can be used to anticipate air quality levels, which is crucial for public health and urban planning.
