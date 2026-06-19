# Chennai Temperature Forecasting Using ARIMA Model

## Project Overview

This project focuses on forecasting Chennai's average temperature using the ARIMA (AutoRegressive Integrated Moving Average) model. The dataset was extracted from the Indian Climate Dataset (2024–2025), and time series forecasting techniques were applied to predict future temperature values.

--------------------------------------------------

## Dataset Information

Dataset        : Indian Climate Dataset 2024–2025
City Selected  : Chennai
Target Variable: Temperature_Avg
Time Period    : 2024–2025

--------------------------------------------------

## Objectives

• Analyze Chennai temperature trends.
• Check stationarity using the Augmented Dickey-Fuller (ADF) Test.
• Identify suitable ARIMA parameters.
• Compare multiple ARIMA models.
• Select the best model using RMSE.
• Forecast temperature for the next 7 days.

--------------------------------------------------

## Methodology

1. Load Climate Dataset
2. Filter Chennai Data
3. Convert Date Column
4. Set Date as Index
5. Data Visualization
6. ADF Stationarity Test
7. ACF & PACF Analysis
8. Train-Test Split (80:20)
9. ARIMA Model Selection
10. Model Evaluation using RMSE
11. 7-Day Temperature Forecasting

--------------------------------------------------


## Forecast Results

The selected ARIMA(1,0,0) model was used to forecast Chennai temperatures for the next 7 days. The forecast values converged toward the historical average temperature of approximately 29.88°C.

--------------------------------------------------

## Conclusion

The Chennai temperature dataset was analyzed using the ARIMA forecasting model. The ADF test confirmed that the series was stationary, eliminating the need for differencing. After evaluating multiple ARIMA models, ARIMA(1,0,0) achieved the lowest RMSE and was selected as the final forecasting model. The model successfully generated a 7-day temperature forecast and demonstrated the application of ARIMA in climate data forecasting.

--------------------------------------------------

## Technologies Used

• Python
• Pandas
• NumPy
• Matplotlib
• Statsmodels
• Scikit-learn
• Google Colab

--------------------------------------------------

## Prepared by

Sugumar Ranganathan

--------------------------------------------------


--------------------------------------------------
