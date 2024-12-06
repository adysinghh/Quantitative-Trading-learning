#### Quantitative Momentum Investing Strategy
---
> [!IMPORTANT]  
> I will keep updating the ReadMe to explain Code in more detail.

### Overview
This project focuses on building a momentum-based investment strategy that identifies and invests in the **top 50 stocks with the HQM **. 

### Optimization
We optimize the results by calculating HQM Score. Then we consider the stocks with top 50 HQM score.

### Background
1. **High Quality Momentum Stock**(HQM): "Slow And Steady" Out-Performance over long period of time.
2. **Low Quality Momentum Stock**(LQM): Stocks which show no momentum(return/performace) for a long time, then have a sudden surge for shorter duration primarly due to factors realted to Sentiment, i.e., News.
3. **HQM Score**: The HQM Score reflects the stock's overall momentum quality. By averaging the percentiles of returns over multiple time periods, it identifies stocks with consistent high performance across different time horizons. A higher HQM Score means the stock exhibits strong momentum over various time frames.

### Features
- **API**: YahooFinance(yfinance)
- **Momentum Metrics**: High-Quality Momentum (HQM) score, based on:
  - 1-month price return.
  - 3-month price return.
  - 6-month price return.
  - 1-year price return.
- **Portfolio Management**: Recommended trades for an equal-weighted portfolio of the top 50 stocks.
- **Outcome**: Demonstrates the effectiveness of momentum as a signal in investment decision-making.

### Library Imports:
```
import numpy as np
import pandas as pd
import requests
import math
from scipy.stats import percentileofscore as score
import xlsxwriter
import yfinance as yf
```

### Install Required:
```
!pip install xlsxwriter
```
