# Bitcoin Price Prediction using LSTM, ARIMA, and SARIMA

## 📊 Project Overview

This project focuses on predicting Bitcoin prices using three different time series forecasting models:

- **Long Short-Term Memory (LSTM) Neural Network**
- **AutoRegressive Integrated Moving Average (ARIMA)**
- **Seasonal AutoRegressive Integrated Moving Average (SARIMA)**

The goal is to compare the models based on standard evaluation metrics and determine the best-performing approach.

---

## ⚙️ Models Used

### 1. Long Short-Term Memory (LSTM)
- A deep learning model that captures long-term dependencies in sequential data.
- Effective in modeling complex, non-linear patterns in financial data.

### 2. ARIMA (AutoRegressive Integrated Moving Average)
- A classical statistical model suited for non-seasonal, stationary data.
- Captures autocorrelation in time series data.

### 3. SARIMA (Seasonal ARIMA)
- Extension of ARIMA that accounts for seasonality.
- Suitable for time series data with trend and seasonal components.

---

## 📈 Evaluation Metrics

| Evaluation Metric           | LSTM      | ARIMA      | SARIMA     |
|-----------------------------|-----------|------------|------------|
| Mean Absolute Error (MAE)    | 4132.45   | 30949.10   | 31765.11   |
| Root Mean Square Error (RMSE)| 4756.34   | 39750.92   | 40430.10   |
| R-Squared (R²)               | 0.9042    | -1.5120    | -1.5987    |

---

## 📝 Key Findings

- **LSTM** achieved the lowest MAE and RMSE and the highest R² score, proving to be the most accurate model.
- Both ARIMA and SARIMA performed poorly, with negative R² scores, indicating that these models were not suitable for this dataset.

---

## 🛠 Technologies Used

- Python
- TensorFlow, Keras
- Scikit-learn
- Statsmodels
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook




