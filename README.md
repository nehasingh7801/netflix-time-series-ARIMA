# Netflix Subscriptions Forecasting

This project forecasts Netflix's subscriber growth using time series analysis with ARIMA. The goal is to analyze historical subscription data, calculate quarterly and yearly growth rates, and forecast future subscription trends.

## Project Overview

- **Data**: The dataset contains Netflix's quarterly subscriber count over several years.
- **Analysis**:
  - Quarterly and yearly growth rates are calculated and visualized.
  - ARIMA (AutoRegressive Integrated Moving Average) model is used to forecast the next 5 quarters of subscriber growth.
  
## Requirements
- Python 3.x
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - plotly
  - statsmodels


## Data

- The dataset should be in CSV format with at least two columns: `Time Period` and `Subscribers`.
- Make sure to adjust the path in the code to the location of your dataset.

## Key Features

1. **Quarterly Growth Rate Calculation**: Measures the change in subscriptions between consecutive quarters.
2. **Yearly Growth Rate Calculation**: Measures the subscription growth for each year.
3. **ARIMA Forecasting**: Forecasts Netflix's subscriber growth for the next 5 quarters.


## Example Output

- Line plots showing Netflix’s subscription growth.
- Bar charts visualizing growth rates.
- Forecast for the next 5 quarters.
