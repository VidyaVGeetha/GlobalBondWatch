# 📈 Global 5-Year Government Bond Yield Comparison (Last 5 Years)

This project analyzes and visualizes the trends in 10-year government bond yields across key global economies over the past five years. The script pulls data from Yahoo Finance (US) and the Federal Reserve Economic Data (FRED) API for other countries, then generates a comparative line chart and summary statistics.

## 🔧 Features

- Fetches US 10-Year Treasury yield using Yahoo Finance (`^TNX`)
- Retrieves historical bond yield data for UK, Germany, France, Italy, Japan, and Australia via the FRED API
- Merges and aligns all data on common dates
- Visualizes all countries’ bond yields on a single plot
- Calculates and prints the average 10-year bond yield per country for the last 5 years

## 📁 Files

- `bond_yield_comparison.py`: Main Python script to retrieve, process, and visualize data
- `README.md`: Documentation file explaining the project, setup, and results

## 🧪 Requirements

Before running the script, ensure you have the following Python packages installed:

```bash
pip install yfinance fredapi pandas matplotlib
