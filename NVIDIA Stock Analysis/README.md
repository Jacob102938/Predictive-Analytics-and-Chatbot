# NVIDIA Stock Price Analysis
## Introduction
OLS regression analysis to identify factors affecting NVIDIA's (NVDA) daily closing price using intraday trading variables.
## Dataset Used
NVIDIA_STOCK.csv — daily OHLCV data for NVIDIA stock.
## Variables

Dependent: Close Price
Independent: Open, High, Low, Volume

## Key Insights

Model achieved a near-perfect R² of 1.000, indicating closing price is almost entirely determined by intraday price variables.

High and Low prices were strong positive predictors; Open had a negative coefficient (higher open → slightly lower close, reflecting intraday market correction).

Volume was statistically insignificant (p-value = 0.617), meaning trading volume does not meaningfully predict the closing price.

Mild heteroscedasticity observed at higher price ranges; multicollinearity exists between price variables.

## Conclusion
NVIDIA's daily closing price can be predicted with high accuracy using High, Low, and Open prices alone. Volume adds no predictive value. The model is robust but should be interpreted cautiously due to multicollinearity.
