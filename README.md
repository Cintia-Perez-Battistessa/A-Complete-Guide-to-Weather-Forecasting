# A Complete Guide to Weather Forecasting
<img width="500" alt="Captura de Pantalla 2024-01-30 a la(s) 21 05 37" src="https://github.com/Cintia-Perez-Battistessa/A-Complete-Guide-to-Weather-Forecasting/assets/129741210/7337f85a-807f-4909-96c9-880cfbc7925c">

>_Figure  1: This graph compares actual and predicted average temperatures in Spain using the SARIMAX model. The shaded region around the predicted values represents the uncertainty range.

<a name="top"></a>
## Table of Contents
* [1. About the Project](#1)
* [2. Project Page](#2)
* [3. Project Data](#3)
* [4. License](#4)
* [5. Give it a Star](#5)


<a name="item1"></a>
## 1. Introduction of the Project

This project describes the step-by-step method for forecasting the mean temperature of Spain through the application of various predictive methods.

The project begins by explaining essential insights into time series and prediction concepts. Following this, details of the preprocessing required to prepare the data for applying prediction algorithms are provided. Subsequently, various prediction methods, including ARIMA, SARIMA, SARIMAX, and PROPHET, are used, validated, and evaluated through relevant metrics.

<a name="2"></a>
## 2. Project objectives

The project objectives were:

- Prepare mean temperature data for Spain to forecast it.
- Predict mean temperature using different methods such as ARIMA, SARIMA, SARIMAX, and Prophet
- Evaluate and compare the prediction models.

<a name="3"></a>
## 3. Project Data

In this project, daily weather data from 1963 to 2022 for each capital of Spain is used to estimate and predict the average weather data for Spain. This dataset, obtained through the Open-Meteo API, was originally collected and processed in a prior GitHub project titled "Climate Change in Spain with Animation.

<a name="4"></a>
## 4. Conclusion

The metrics for the various predictive models are summarized in the table below.

>_Table  1: Comparison table of predictive model metrics.

<img width="392" alt="Captura de Pantalla 2024-01-30 a la(s) 21 06 43" src="https://github.com/Cintia-Perez-Battistessa/A-Complete-Guide-to-Weather-Forecasting/assets/129741210/ead066e0-e941-47ce-b27f-6b8c9f339b69">

The ARIMA model exhibits the lowest performance, as it does not consider the seasonality inherent in the data. On the other hand, SARIMA, which incorporates stationarity, significantly improves precision by capturing data patterns better. The introduction of exogenous variables (maximum wind speed and total precipitation) in the SARIMAX model results in an improved R2 metric. While both SARIMA and SARIMAX effectively capture data patterns, the presence of overfitting signals is indicated by model residuals. The simpler Prophet model successfully captures data patterns but achieves comparatively lower precision than SARIMA and SARIMAX.

A notable observation is that none of the models accounts for the increasing trend in temperature over the years.

<a name="5"></a>
## 5. License 
This project is licensed under the Apache License. Please take a look at the LICENSE file for more information.

<a name="item6"></a>
## 6. Give it a Star! ⭐ 
If you find this helpful, please star it. Thanks!
