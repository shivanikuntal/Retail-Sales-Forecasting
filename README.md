# Retail Sales Forecasting

## About the Project

This project focuses on analyzing historical retail sales data to understand sales trends, identify seasonal patterns, and forecast future demand.

I used Python for data cleaning and analysis and a time series forecasting model to predict upcoming sales. The project also explores how sales forecasts can help businesses plan inventory and prepare for periods of high demand.

## Project Objectives

- Analyze historical retail sales data.
- Identify sales trends and seasonal patterns.
- Find peak sales periods.
- Forecast future sales using time series analysis.
- Compare actual sales with predicted sales.
- Provide inventory and restocking recommendations based on forecast trends.

## Dataset

The project uses the **Retail Data Analytics dataset** from Kaggle.

Dataset link: https://www.kaggle.com/datasets/manjeetsingh/retaildataset

The dataset includes historical sales information for different stores and departments, along with dates that can be used to analyze sales over time.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Statsmodels
- Google Colab
- Jupyter Notebook

## Project Workflow

1. Loaded the dataset using Pandas.
2. Inspected the data structure, missing values, duplicates, and data types.
3. Cleaned the data and converted dates into the appropriate format.
4. Aggregated sales into a weekly time series.
5. Analyzed historical sales trends and seasonal patterns.
6. Identified peak sales periods.
7. Built a Holt-Winters Exponential Smoothing model.
8. Evaluated the model using MAE, RMSE, and MAPE.
9. Compared actual sales with predicted sales using line charts.
10. Forecasted sales for the next 12 weeks.
11. Developed inventory and restocking recommendations.

## Forecasting Model

This project uses **Holt-Winters Exponential Smoothing**, a time series forecasting method that can model:

- Trend in sales over time
- Seasonal variations in demand
- Future sales based on historical patterns

The model is evaluated on a holdout test period before being fitted to the complete historical series for future forecasting.

## Key Analysis

- Historical weekly sales trends
- Average sales by calendar month
- Peak-demand weeks
- Seasonal decomposition
- Actual vs. predicted sales
- Future 12-week sales forecast
- Store-level sales performance

## Model Evaluation

The project calculates the following metrics:

- **MAE:** Mean Absolute Error
- **RMSE:** Root Mean Squared Error
- **MAPE:** Mean Absolute Percentage Error

These metrics help assess how closely the model's predictions match actual sales during the test period.

## Inventory and Restocking Recommendations

The forecast is used to examine expected demand and provide basic recommendations, such as:

- Increasing safety stock when demand is expected to rise.
- Monitoring peak-demand periods to prepare for higher sales.
- Avoiding excessive inventory when demand is expected to decline.
- Reviewing forecasts regularly as new sales data becomes available.

These recommendations are based on aggregated sales forecasts. Actual inventory decisions should also consider product-level demand, supplier lead times, stock on hand, and stockout risk.

## Conclusion

This project demonstrates how historical retail sales data can be used to understand demand patterns and forecast future sales. It combines data cleaning, exploratory analysis, time series forecasting, model evaluation, and business recommendations in one workflow.

## Skills Demonstrated

**Python | Pandas | NumPy | Time Series Analysis | Holt-Winters Forecasting | Seasonality Analysis | Data Visualization | Model Evaluation | Inventory Planning | Business Analysis**
