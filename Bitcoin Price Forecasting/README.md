# Bitcoin Price Forecasting

## Introduction
Predictive analytics project on Bitcoin's historical price data using multiple statistical and machine learning techniques.
## Dataset Used
coin_Bitcoin.csv — historical Bitcoin OHLC (Open, High, Low, Close) price data.
## Variables

Dependent: Close Price
Independent: Open, High, Low prices; Date (for time series)

## Key Insights

OLS regression showed a strong linear relationship between Open and Close prices.

Multiple Linear Regression (MLR) using Open, High, and Low together yielded near-perfect predictions.

30-day Moving Average smoothed out price volatility trends.

Single Exponential Smoothing (SES) and Double Exponential Smoothing (DES) were applied for short-term forecasting; DES performed better by capturing the trend component.

## Conclusion
Intraday price variables (High, Low, Open) are strong predictors of Bitcoin's closing price. Time series models help capture trend patterns, with DES being more suitable for a trending asset like Bitcoin.
