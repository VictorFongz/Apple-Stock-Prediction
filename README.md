# Apple-Stock-Prediction Repository
![image](https://github.com/VictorFongz/Apple-Stock-Prediction/assets/143273160/5c4578ca-67dd-49ae-8524-db535eda8a32)

## About
This repository contains a simple data science project focused on predicting the stock prices of Apple Inc. using various machine learning models. The primary objective of this project is to showcase the application of different predictive models in the context of financial time series data. By leveraging historical stock price data, this project explores and compares the performance of multiple models, including Auto-Regressive Integrated Moving Average (ARIMA), Seasonal Auto-Regressive Integrated Moving Average including Exogenous factors (SARIMAX) and Long Short-Term Memory (LSTM) neural networks.

## Problem Definition and Motivation
Predicting stock prices is a challenging due to the volatility and complexity of the stock markets yet it is a crucial task in the financial industry. Accurate stock price predictions help investors determine the intrinsic value of a stock, which is essential for making informed investment decisions. The intrinsic value of a stock is a measure of its true worth based on future earnings, dividends, and growth potential, as opposed to its current market price. The specific problem addressed in this project is to develop models that can predict the future stock prices of Apple Inc. based on historical price data. By leveraging various machine learning models, this project aims to accurately forecast stock prices. While the focus is on Apple Inc., the methodologies and models developed can be extended to predict the stock prices of other companies as well.

## Dataset
The dataset used for this project is sourced from Yahoo Finance. It includes historical stock prices of Apple Inc. from `2015-01-02` to `2024-05-20`. The features include date, open price, high price, low price, close price, adjusted close price, and volume.

## Approach
1. **Data Collection**: Through the use of yfinance open source library, retrieved historical stock prices from Yahoo Finance.
2. **Data preprocessing**: Cleaned and prepared the data for analysis and make it usable by machine learning models
3. **Exploratory Data Analysis**: Analysed trends and patterns in the data. This includes data visualisation of the closing stock price, understanding the trends and seasonality of the data. Statistical analysis to determine the stationarity of the dataset.
4. **Model Development**: Utilised carious machine learning algorithms to build predictive models
5. **Model Evaluation**: Assessed the model's performance using metrics like Root Mean Squared Error (RMSE) and Mean Square Error (MSE)

## Models Used
- ARIMA
- SARIMAX
- LSTM Neural Network

## Results
- ARIMA: RMSE = 
- SARIMAX: RMSE = 
- LSTM Neural Network: RMSE = 

## Conclusion
The SARIMAX model outperformed the other models in predicting stock prices, achieving the lowest RMSE. Future work could involve hyperparameter tuning and incorporating additional features beyond historical prices, such as a stock's beta, P/E ratio, dividend policy and other financial metrics, to enhance prediction accuracy. Additionally, exploring more advanced models could further improve performance.
