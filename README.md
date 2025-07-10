# Cointegration Analysis of Stock Pairs

This project implements a basic **cointegration test** between two stock time series — ExxonMobil (XOM) and Chevron (CVX) — using Python libraries like `yfinance`, `matplotlib`, `scipy`, and `statsmodels`.

## 📈 Overview

Cointegration is a statistical technique used to identify a long-term equilibrium relationship between two time series. This can be useful in **pairs trading**, where the spread between cointegrated assets is exploited for profit.

This implementation:
- Downloads historical stock price data using `yfinance`
- Visualizes the price movements and their scatter relationship
- Applies **linear regression** to create a residual spread
- Performs the **Augmented Dickey-Fuller (ADF) test** to check for stationarity of the spread

## 🛠️ Features

- ✅ Data download via `yfinance`
- 📊 Dual time series plotting
- 🔍 Scatter plot visualization
- 📉 Linear regression-based residual calculation
- 📌 ADF test for cointegration detection

## 🧪 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/cointegration-analysis.git
   cd cointegration-analysis
