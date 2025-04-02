# 🌍 Global Internet Forecast (ARIMA Model)
A data science project forecasting global internet usage trends using ARIMA time series modeling. Predicts adoption rates across countries for the next decade.

**Forecasting worldwide internet adoption trends using time series analysis**

## 📌 Overview
This project predicts future internet penetration rates (2024-2033) for 200+ countries using ARIMA time series modeling. It includes:
- Data cleaning for irregular time series
- Automated ARIMA parameter tuning
- Visualization of historical vs. forecasted trends
- Exportable forecast results in CSV/Excel

## 📂 Dataset
Source: [kaggle.com]([(https://www.kaggle.com/datasets/meleknur/global-internet-usage-by-country-2000-2023/data])
Format: CSV with columns:
- `Country Name`, `Country Code`
- Yearly internet usage (% population) from 2000-2023

## 🛠️ Installation
```bash
git clone https://github.com/rushikeshya/global-internet-forecast-arima.git
```
## 📊 Sample Output
![image](https://github.com/user-attachments/assets/ae7a8869-315e-431c-9386-bfc1b4adb794)


## 📈 Key Features
✅ Automated missing data handling

✅ Grid search for optimal ARIMA (p,d,q) parameters

✅ Confidence interval calculation

✅ Regional aggregation (Continents/Income Groups)
