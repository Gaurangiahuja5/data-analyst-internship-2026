# Week 2: Creating Financial Forecasts

This week's task was to build a basic financial forecasting model using the same
bank customer dataset from Week 1.

## What I Did

- Chose **Average Account Balance by Tenure** as the financial indicator to forecast,
  using Tenure (years as a customer) as a stand-in for time since the dataset has
  no calendar dates
- Designed a simple **linear trend model**, justified by the small number of data
  points (11) and the absence of any seasonal pattern
- Implemented the model by fitting a straight line through the average balance for
  each tenure year, then projected it forward to tenure years 11–15
- Visualized the actual data against the forecasted trend in a single chart
- Evaluated the forecast's reliability using R² (R-squared), which came out to
  0.360 — showing the trend is real but only explains about a third of the
  variation in balance

## Key Result

Average balance is forecasted to decline from about **$74,439** at tenure year 11
to about **$73,046** at tenure year 15, a mild downward trend of roughly $348 per
year. However, with an R² of only 0.360, this should be read as a general
directional estimate rather than a precise prediction.

## Files

- `Customer_churn.ipynb` — the full analysis notebook, including both the Week 1
  churn analysis and the Week 2 financial forecast (see the "Week 2" section within it)
