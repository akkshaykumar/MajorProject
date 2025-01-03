# Weather Data Analysis, Anomaly Detection, and Forecasting

## Overview

This project performs detailed analysis, anomaly detection, and forecasting of weather data. It processes historical weather data, identifies extreme weather conditions, and predicts future trends using machine learning models and time-series analysis techniques.

## Features

1. **Data Preprocessing:**
   - Handles missing values for temperature and precipitation.
   - Converts date formats and filters data for analysis.

2. **Exploratory Data Analysis (EDA):**
   - Displays statistical summaries and visualizes distributions of weather parameters (PRCP, TAVG, TMAX, TMIN).

3. **Data Aggregation and Smoothing:**
   - Aggregates daily data and applies smoothing for trend analysis.

4. **Anomaly Detection:**
   - Identifies anomalies using Isolation Forest and One-Class SVM.
   - Analyzes the correlation of anomalies with extreme weather events.

5. **Time Series Forecasting:**
   - Implements ARIMA, SARIMA, and Exponential Smoothing (ETS) models for precipitation forecasting.
   - Compares model performance using error metrics (RMSE, MAE).

6. **Visualization:**
   - Plots smoothed weather trends, anomaly detection results, and model forecasts.

## Requirements

The project requires Python 3.9 or above and the following Python libraries:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scipy`
- `statsmodels`
- `sklearn`

Install dependencies using the following command:
```bash
pip install numpy pandas matplotlib seaborn scipy statsmodels scikit-learn



```python

```
