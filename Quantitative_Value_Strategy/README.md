# Value Investing Strategy

This project implements a **robust value investing strategy** using multiple valuation metrics to identify undervalued stocks.

## AIM
1. To Build a simple Value Strategy that relies on one metric (Here I used Price/Earning ratio)
2. Then, We Will Improve that Value Stratgy by creating a `Composite Value` that takes into account many different metrics, when trying to estimate Intrinsic Value, then we take their Percentiles and Calculate RV Score `Robust Value`

## Features
- **Metrics Used**:
  - Price-to-Earnings (P/E) Ratio.
  - Price-to-Book (P/B) Ratio.
  - Price-to-Sales (P/S) Ratio.
  - EV/EBITDA.
  - EV/GP.
- **Scoring System**: 
  - Calculated percentiles for each metric.
  - Computed the **RV Score**: Average of all percentiles.
- **Outcome**: A comprehensive value investing approach that overcomes the limitations of individual metrics.

## Library to import:
```
import numpy as np
import pandas as pd
import xlsxwriter as xl
import requests as rq
from scipy import stats
import math
import yfinance as yf
```

