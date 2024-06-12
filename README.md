# Avocado Price Forecasting using ARIMA and SARIMA
This project involves the analysis and forecasting of avocado prices using ARIMA and SARIMA models in R. The study replicates and extends the work presented in Avocado Price Forecasting using ARIMA and SARIMA on Kaggle. The goal is to translate the original analysis from Python to R, reproduce the results, and introduce improvements or changes to enhance the model's performance and insights.


## Project Objectives
Translation to R: Convert the original Python code for avocado price forecasting into R.    
Reproduce Original Results: Attempt to reproduce the original results as closely as possible in R.  
Introduce Improvements: Explore and implement potential improvements or changes to the model and assess their impact on the conclusions.

## Data Description
The dataset contains historical avocado prices and sales volume data from various regions in the United States, spanning from 2015 to 2018. The key variables include:
Date: The date of the observation.  
AveragePrice: The average price of a single avocado.    
Total Volume: The total number of avocados sold.
4046, 4225, 4770: The total number of avocados sold for each PLU (Price Look-Up) code.
Total Bags, Small Bags, Large Bags, XLarge Bags: The total number of bags sold and their respective sizes.
Type: The type of avocado (conventional or organic).    
Year: The year of the observation.  
Region: The region where the observation was recorded

## Methodology
1. Data Preprocessing
Load and inspect the dataset.
Handle missing values and perform necessary data cleaning.
Create additional features if required, such as log transformation and differencing.

2. Exploratory Data Analysis (EDA)
Plot the time series of AveragePrice to visualize trends and seasonality.Compute and plot the autocorrelation function (ACF) and partial autocorrelation function (PACF) to understand the temporal dependencies.

3. Testing for Stationarity
Perform Dickey-Fuller and Augmented Dickey-Fuller (ADF) tests to check for stationarity.Apply log transformation and differencing to achieve stationarity.

4. Time Series Decomposition
Decompose the log-transformed and differenced time series to analyze trend, seasonality, and residuals.

5. Model Fitting
Fit ARIMA and SARIMA models to the transformed time series.
Evaluate model performance using standard metrics.

6. Forecasting
Generate forecasts using the fitted models.Plot the forecasted values and compare them with the actual values.

7. Model Improvements
Explore potential improvements or changes to the model.
Assess the impact of these changes on the model's performance and conclusions

## Conclusion
This project successfully replicates and extends the avocado price forecasting analysis using ARIMA and SARIMA models in R. By translating the original Python code, reproducing the results, and introducing improvements, we gain deeper insights into the time series behavior and forecasting capabilities. The findings and methodologies can be further applied to similar time series forecasting problems in econometrics and other fields.
