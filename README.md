# Electricity Demand Estimation for Leading Distributor

## Project Overview
This project focuses on analyzing historical electricity consumption patterns and developing predictive models to estimate future demand. By leveraging time series forecasting techniques, we aim to enable efficient resource allocation and strategic planning for the electricity distributor.

## Objectives
- Analyze historical electricity demand data.
- Build and evaluate ARIMA, SARIMAX, and ETS models.
- Identify the best-performing model for accurate forecasting.

## Approach

### 1. Data Exploration and Preprocessing
- **Data Cleaning:** Handled missing values and ensured consistency in time series data.
- **Visualization:** Used line plots and seasonal decomposition to understand trends and seasonality.
- **Stationarity Checks:** Applied ADF test and differencing to ensure stationarity.

### 2. Model Development
- **ARIMA (AutoRegressive Integrated Moving Average):** Captured linear dependencies in time series data.
- **SARIMAX (Seasonal ARIMA with Exogenous Factors):** Modeled seasonal effects and external influences.
- **ETS (Error, Trend, and Seasonality):** Provided flexible modeling of trend and seasonal components.

### 3. Model Evaluation
- **Performance Metrics:** Compared models using RMSE and RMSPE.
- **Best Model:** ETS model outperformed others, achieving high forecasting accuracy.

### 4. Forecasting and Insights
- Generated demand forecasts for the next 2 years.
- Provided actionable insights for optimizing resource allocation.

## Results
- **ETS model achieved the highest accuracy**, making it the preferred choice for forecasting.
- **Improved demand estimation** enables better planning and operational efficiency.
## Technologies Used
- **Python** (pandas, numpy, statsmodels, scikit-learn)
- **Time Series Forecasting** (ARIMA, SARIMAX, ETS)
- **Data Visualization** (matplotlib, seaborn)
- **Model Evaluation** (RMSE, RMSPE)
