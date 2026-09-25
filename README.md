# Financial-Forecasting-Week-2
Week 2 financial forecasting using Python, Pandas, Matplotlib, and a 3-month moving average model.
# Financial Forecasting – Week 2

## Project Overview

This project was completed as part of Week 2 of my internship.

The objective is to develop a basic financial forecasting model using the UCI Bank Marketing dataset.

## Objective

The main objective of this project is to:

- Select a relevant financial indicator
- Prepare the historical data
- Build a simple forecasting model
- Generate future forecasts
- Evaluate the forecasting performance
- Analyze the forecast results

## Selected Indicator

The selected indicator is:

**Monthly Term-Deposit Subscription Rate (%)**

Subscription Rate is calculated as:

Subscription Rate = (Successful Subscriptions / Total Customers Contacted) × 100

## Dataset

The project uses the UCI Bank Marketing dataset.

The dataset contains customer information related to a bank's marketing campaign.

## Methodology

The following steps were performed:

1. Loaded the dataset using Pandas.
2. Converted the target variable into numerical values.
3. Grouped the data by month.
4. Calculated the monthly subscription rate.
5. Applied a 3-month moving average.
6. Forecasted the subscription rate for upcoming periods.
7. Evaluated the model using Mean Absolute Error (MAE).
8. Visualized the actual and forecasted values.

## Forecasting Model

A **3-month moving average** model was used.

The forecast is calculated using the average subscription rate of the latest three months.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Results

The model produces a forecast of the expected monthly term-deposit subscription rate.

The forecast results and evaluation metrics are available in the Jupyter Notebook and project report.

## Conclusion

A basic financial forecasting model was successfully developed using historical bank marketing data. The 3-month moving average provides a simple and understandable method for estimating future subscription rates.

## Author

Ishita Paul
