# Stock Forecasting with Prophet

This project evaluates the open-source time series forecasting tool **Prophet**, developed by Facebook. It is widely used in scientific and financial applications for analyzing and predicting future trends using time series data.

Prophet is a programming tool, built as a Python library, designed to handle time series with strong seasonal effects and historical trends. In this project, we demonstrate its use in forecasting stock market prices using historical stock data downloaded via the `yfinance` library.

---

## Installation

To install the necessary Python libraries, use the commands below.

If you’re using a Jupyter notebook, run:

```python
%pip install yfinance prophet pandas matplotlib
```

## Example Code

See `stock_forecast.ipynb` for full example. The notebook:
- Downloads Apple (AAPL) stock data using `yfinance`
- Trains a Prophet model on the historical data
- Forecasts 30 days into the future
- Saves a plot as `forecast_plot.png`

## Submission Script

To execute the notebook and generate the forecast:

```bash
bash run.sh
