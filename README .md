# 📈 Time Series Analysis & Forecasting (TSAF) Assignment

This repository contains a complete time series forecasting assignment completed for the **AtomCamp AI Bootcamp**.

We forecast stock prices using both classical statistical methods and deep learning techniques.

---

## 📌 Objective

To build forecasting models on historical stock price data using:

- 🔹 ARIMA (AutoRegressive Integrated Moving Average)
- 🔹 LSTM (Long Short-Term Memory neural network)

---

## 📊 Dataset

- Source: [Yahoo Finance](https://finance.yahoo.com/)
- Stock: `AAPL` (Apple Inc.)
- Period: 2018–2023 (5 years of daily data)
- Tool used for data download: `yfinance`

---

## 🛠️ Methods & Workflow

### 1. Time Series Analysis
- Line plot of Close prices
- Rolling averages (7-day & 30-day)
- Seasonal decomposition
- ADF Test for stationarity
- ACF/PACF plots for lag analysis

### 2. ARIMA Forecasting
- Model fitted on differenced series
- (p,d,q) parameters selected manually (can be auto-tuned)
- 30-day future forecast with confidence intervals
- Evaluation: MAE, RMSE

### 3. LSTM Forecasting
- Supervised learning format via sliding window
- Scaled inputs using `MinMaxScaler`
- 2-layer LSTM model
- Evaluation: MAE, RMSE

---

## 📉 Results

- ARIMA and LSTM were both applied and visually compared.
- LSTM demonstrated better performance on unseen test data, capturing non-linear stock movements more effectively.

---

## 📎 Files

| File | Description |
|------|-------------|
| `TSAF_Assignment_Stock_Forecasting.ipynb` | Complete Colab notebook with code, plots, and model results |
| `README.md` | You're reading it! Describes project structure and objective |

---

## 🧠 Final Reflection

> ARIMA is useful for linear, stationary data.  
> LSTM, although data-hungry, captures complex temporal patterns.  
> For stock prices, LSTM provided better generalization in this task.

---

## 👨‍💻 Author

- Name: Faizan Shaikh
- Bootcamp: AtomCamp – AI & Datascience
- GitHub: FaizanShaikh01-rgb

---
