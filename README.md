# Infosys Stock Price Forecasting with Time Series Analysis
Introduction to time series preprocessing and forecasting in Python using AR, MA, ARMA, ARIMA, SARIMA and SARIMAX model with forecast evaluation.

# Problem Statement
Evaluating Forecast for Infosys Stock from August 2018 to August 2023

You are provided with a dataset containing 1,235 rows and 7 columns of historical data related to Infosys stock. Your objective is to perform a comprehensive evaluation of this dataset and develop forecasts for Infosys stock prices for the period from August 2018 to August 2023. The dataset includes the following columns:

Date: The date of the stock price data points.
Open: The opening price of Infosys stock on a given date.
High: The highest price of Infosys stock on a given date.
Low: The lowest price of Infosys stock on a given date.
Close: The closing price of Infosys stock on a given date.
Volume: The trading volume of Infosys stock on a given date.
Adjusted Close: The adjusted closing price of Infosys stock on a given date.

# 🛠 Tools Used
Tools used:

Google Colab (library: Seaborn, Matplotlib, Pandas, Numpy, statsmodels and sklearn)

Excel
# Documentation
# Python Analysis:-
Table of Contents
Introduction
Getting Started
Data Preparation
Seasonal Decomposition
Train-Test Split
Stationarity Check
Time Series Models
SARIMAX Model
Exogenous Variables
Results
# Introduction
In this project, we aim to forecast Infosys stock prices for the period from August 2018 to August 2023. The key steps in the analysis include data preparation, time series decomposition, model selection, and using the SARIMAX model with exogenous variables to make forecasts.

# Getting Started
To get started, clone this repository to your local machine and make sure you have the necessary Python packages installed. You can do this using pip:

# Data Preparation
Load the dataset, making the date column the index.

# Clean and preprocess the data, handling missing values if necessary.

# Seasonal Decomposition
Perform seasonal decomposition of the data to understand trends, seasonality, and residuals.

# Train-Test Split
Split the data into a training set (70%) and a testing set (30%) for model evaluation.

# Stationarity Check
Conduct the Dickey-Fuller test to check the stationarity of the time series data.

# Time Series Models
Run the ARIMA model and SARIMA model to identify the most suitable parameters for forecasting.

# SARIMAX Model
Implement the SARIMAX model and introduce exogenous variables to improve forecasting accuracy.

# Exogenous Variables
Explore the impact of exogenous variables on the forecasting model.

# Results
Display the Minimum AIC value obtained during model selection.

Evaluate the model's performance using Root Mean Squared Error (RMSE) for ARIMA and SARIMAX.

Visualize Autocorrelation Function (ACF) and Partial Autocorrelation Function (PACF) plots for model diagnostics.

Conclude with the test RMSE values for ARIMA and SARIMAX models and compare the performance. Highlight the significant reduction in RMSE achieved by incorporating exogenous variables in the SARIMAX model.

## Results

The following table summarizes the results of the Infosys stock price forecasting:

| Model                   | Test RMSE |
|------------------------ |:---------:|
| ARIMA(1,1,1)            | 146.16   |
| SARIMAX(1,1,2)(0,0,2,6) | 20.11 |

- **Model**: The name of the forecasting model used.
- **Test RMSE**: The Root Mean Squared Error (RMSE) value for the test dataset.

The SARIMAX(1,1,2)(0,0,2,6) model outperformed the ARIMA(1,1,1) model significantly, reducing the RMSE value from 146.16 to 20.11, indicating a more accurate forecast.

![image](https://github.com/YogenderS/Infosys-Stock-Time-Series-Analysis/assets/111232917/b224e08d-aa59-4699-acec-53048383ce7a)

Link 

