# 🚗 Time Series Analysis and Forecasting

A comprehensive **Time Series Analysis and Forecasting** project developed as part of the **IBM Machine Learning Professional Certificate – Specialized Models: Time Series and Survival Analysis**.

The project focuses on understanding historical time-series behavior and applying statistical, forecasting, and deep-learning techniques to predict future values.

The main final project analyzes **monthly U.S. Light Weight Vehicle Sales** from 1976 to 2022 and compares multiple forecasting approaches, including smoothing methods, SARIMA, Prophet, and a neural-network-based model.

---

## 📌 Project Overview

Time series forecasting is an important area of data science used to analyze observations collected sequentially over time and predict future values.

This project follows a progressive approach, starting with exploratory analysis and statistical testing before moving toward more advanced forecasting techniques.

The major stages of the project include:

- Data loading and preprocessing
- Exploratory Data Analysis
- Time-series visualization
- Trend and seasonality analysis
- Distribution analysis
- White-noise analysis
- Stationarity testing
- Autocorrelation Function (ACF)
- Partial Autocorrelation Function (PACF)
- Time-series smoothing
- Simple Average forecasting
- Single Exponential Smoothing
- Double Exponential Smoothing
- Triple Exponential Smoothing
- SARIMA/SARIMAX forecasting
- SARIMA parameter tuning
- Future forecasting
- Facebook Prophet
- Neural Network forecasting
- Model evaluation
- Model comparison
- Conclusions and future improvements

---

# 🎯 Objectives

The primary objectives of this project are:

1. Analyze historical monthly lightweight vehicle sales.
2. Understand the underlying characteristics of the time series.
3. Investigate trend and seasonal patterns.
4. Determine whether the time series exhibits stationarity.
5. Analyze autocorrelation and partial autocorrelation.
6. Apply different smoothing techniques as baseline forecasting methods.
7. Build a SARIMA/SARIMAX forecasting model.
8. Tune SARIMA parameters using automated model selection.
9. Generate future sales forecasts.
10. Explore Facebook Prophet as an alternative forecasting approach.
11. Implement a neural-network-based forecasting model.
12. Evaluate forecasting performance using MSE and RMSE.
13. Compare different forecasting approaches.
14. Identify limitations and possible future improvements.

---

# 📊 Main Dataset

## Light Weight Vehicle Sales

The primary dataset used in the final project is the **U.S. Light Weight Vehicle Sales** time series.

The original dataset contains the `LTOTALNSA` variable, which represents light-weight vehicle sales. During preprocessing, the variable is renamed to `SALES` for easier analysis.

| Property | Description |
|---|---|
| Dataset | Light Weight Vehicle Sales |
| Original Variable | `LTOTALNSA` |
| Project Variable | `SALES` |
| Frequency | Monthly |
| Time Period | 1976–2022 |
| Number of Observations | 555 |
| Units | Thousands of vehicles |
| Date Format | `YYYY-MM-DD` |

### Example

```text
DATE        SALES
1976-01-01  864.600
1976-02-01  973.300
1976-03-01  1216.100
