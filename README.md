# Time Series Analysis on Crime Data 📊
![crime-data-time-series](https://socialify.git.ci/navyadua/crime-data-time-series/image?language=1&owner=1&name=1&stargazers=1&theme=Light)
## Overview

This project involves analyzing crime data through time series methods to forecast future crime rates. The analysis includes data preprocessing, exploratory data analysis (EDA), and the application of various time series modeling techniques. 🔍📈

## Importing Libraries

The analysis utilizes several R libraries, including `readxl`, `dplyr`, `lubridate`, `ggplot2`, `tseries`, `forecast`, and `MASS`, for data manipulation, visualization, and time series modeling. 📚🔧

## Data Import and Preprocessing

The dataset `merged_crime_data.csv` is loaded and processed to aggregate crime counts by date. The data is then re-sampled to compute monthly average crime rates and grouped by year to facilitate further analysis. 🗂️📅

## Exploratory Data Analysis

Exploratory Data Analysis (EDA) includes:

- Analyzing the distribution of crimes by day of the week to understand daily patterns. 📅🔍
- Examining crime volumes across various geographic areas to identify high-crime regions. 🌍📊

## Time Series Analysis

### Stationarity Check and Data Transformation

- The time series data is checked for stationarity using the Augmented Dickey-Fuller test. Various transformations, including log, square root, and reciprocal, are applied to stabilize the variance and make the data stationary. 📉🔄

### Model Fitting and Forecasting

- **SARIMA Model:** Seasonal Autoregressive Integrated Moving Average (SARIMA) models are fitted to the transformed data to forecast future crime rates. Model performance is evaluated using accuracy metrics and residual diagnostics. 📈🔮
- **Holt's Winter Model:** Holt’s Winter model is applied to capture seasonality and trend in the data. Forecasts are compared against those from the SARIMA model. ❄️📊

## Results

The results section summarizes the performance of different models, including:

- The best-performing model based on Akaike Information Criterion (AIC) and forecasting accuracy. 🏆📉
- Insights from the forecasts and any significant patterns or anomalies identified in the crime data. 🔍✨

## Future Work

Future work may involve:

- Integrating additional features or external variables to enhance model performance. 🔬📊
- Applying advanced forecasting techniques or machine learning methods. 🤖🔍
- Expanding the analysis to cover other regions or longer time periods for a broader understanding of crime trends. 🌍📅

---

Thank you for checking out our project!😉 We believe in creating a better world through technology⚙️, and we hope this project contributes to that goal.👍🏻
