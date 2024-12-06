# S&P 500 Equal Weight Screener

### Overview
This project implements an **equal-weighted version of the S&P 500 index**. Unlike the traditional index, where larger companies dominate due to market capitalization, this version gives equal importance to every stock.

### Goal
The goal of this section of the course is to create a Python script that will accept the value of your portfolio and tell you how many shares of each S&P 500 constituent you should purchase to get an equal-weight version of the index fund.

### Features
- **API**: Tiingo API for stock data.
- **Dataset**: S&P 500 stock list.
- **Implementation**:
  - Calculated equal weights for all 500 companies.
  - Saved the results to an Excel file using `xlsxwriter`.
- **Outcome**: A fresh perspective on index performance without market-cap bias.

### Libray Imports
- numpy
- pandas
- requests
- xlsxwriter
- math
- scipy.stats
- statistics.mean
- yfinance

> [!WARNING]
> Run This To Avoid Errors: ```!pip install pandas==1.3.3 pandas-datareader==0.9.0```
