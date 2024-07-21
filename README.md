
---

# 💊 Pharma Sales Data Analysis and Forecasting

## 🎯 Objective
The study aims to evaluate various methods for preparing, analyzing, and forecasting sales data of pharmaceutical products on a small scale. This involves assessing forecasting accuracy and recommending strategies based on trends and seasonality for individual distributors, pharmacy chains, or even single pharmacies.

## 📚 Introduction
While the **Naïve model** is commonly used in large-scale pharmaceutical sales forecasting, it often fails when markets saturate. On a smaller scale, accurate forecasting is crucial for resource planning and business decisions. The research explores modern time-series forecasting techniques and compares their accuracy to traditional methods like **Naïve, Seasonal Naïve, and Average models**.

## 🛠️ Methodology

### 📊 Data Preparation
- **Sales data** from a Point-of-Sale system of a single pharmacy over six years is cleaned and transformed into hourly time series.
- Data includes various pharmaceutical product groups with distinct characteristics, such as anti-inflammatory, analgesics, psycholeptics, etc.
- Anomalies and outliers are identified and treated, and data is rescaled to a weekly frequency.

### 📈 Time-Series Analysis
- Analysis at annual, weekly, and daily levels is conducted to derive insights for sales and marketing.
- **Stationarity, autocorrelation, and predictability** of time series are examined to determine initial parameters for forecasting.

### 🔮 Forecasting
- Two approaches are used: **rolling forecasts** (short-term) and **long-term forecasting**.
- **Models Tested**: ARIMA/SARIMA, Facebook Prophet, and Long-Short Term Memory (LSTM) neural networks.

### 🔧 Hyper-parameter Optimization
- ARIMA and Prophet models use **grid search**.
- LSTM models include **Vanilla, Stacked, and Bidirectional** architectures.
- **Evaluation**: Mean Squared Error (MSE) and Mean Absolute Percentage Error (MAPE) are used to measure accuracy. Baseline comparisons include Naïve and Seasonal Naïve models for rolling forecasts and Average methods for long-term forecasting.

## 🗝️ Key Findings
- The study reveals the feasibility and performance of modern forecasting methods compared to basic models.
- It provides insights into selecting appropriate forecasting techniques based on the nature of the sales data and forecasting horizon.

---
