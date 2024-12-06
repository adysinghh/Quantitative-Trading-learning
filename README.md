# Quantitative-Trading-learning

> [!TIP]  
> Star The Repository If It Helped You!  

> [!IMPORTANT]  
> I'm continually adding more projects as I learn new strategies. I will keep updating the ReadMe to explain everything in more detail.
 
## Usage
Clone the repository:
```
git clone https://github.com/adysinghh/Quantitative-Trading-learning.git
```

Welcome to my **Quantitative Trading Learning** repository! This repository serves as my personal journey into the world of quantitative trading, Here I will Add Projects that used ML and Non-ML Algorithms. Each project here is a hands-on implementation inspired by tutorials I followed on YouTube, but with my own unique modifications, such as the use of different APIs and datasets, resulting in varying syntax and methodologies. 

The goal of this repository is to explore and apply quantitative trading strategies to build a strong understanding of the principles behind them. 

---

## Projects in This Repository 📂 

### 1. **S&P 500 Equal Weight Screener**
- **Objective**: Create a version of the S&P 500 index that equal weights all the stocks, unlike the traditional index where larger companies have a higher weight due to market capitalization.
- **Implementation**: 
  - Utilized the **Tiingo API** and an S&P 500 dataset.
  - Rebalanced the index to assign equal weights to each stock.
- **Outcome**: This equal-weighted index provides a different perspective on how the S&P 500 would perform if every company carried the same weight, Saved the results in an Excel file using `xlsxwriter`.

---

### 2. **Quantitative Momentum Investing Strategy**
- **Objective**: Build a momentum-based investment strategy that selects the top 50 stocks with the highest price momentum.
- **Implementation**: 
  - Calculated **High-Quality Momentum (HQM)** scores using percentile ranks for:
    - 1-month price return , 3-month price return, 6-month price return and 1-year price return.
  - Recommended trades for an equal-weighted portfolio of these 50 stocks.
- **Outcome**: This project demonstrates the power of momentum as a trading signal, prioritizing stocks that have shown strong price performance, Saved the results in an Excel file using `xlsxwriter`.

---

### 3. **Value Investing Strategy**
- **Objective**: Develop a robust value investing strategy using multiple valuation metrics to overcome the limitations of individual metrics.
- **Implementation**:
  - Used metrics like:
    - **Price-to-Earnings Ratio** (P/E).
    - **Price-to-Book Value Ratio** (P/B).
    - **Price-to-Sales Ratio** (P/S).
    - **Enterprise Value to EBITDA** (EV/EBITDA).
    - **Enterprise Value to Gross Profit** (EV/GP).
  - Calculated an **RV Score**: The average of all percentile ranks across these metrics.
- **Outcome**: This strategy identifies undervalued stocks by balancing out the flaws of individual valuation metrics, Saved the results in an Excel file using `xlsxwriter`.

---

### What's Next?🧑🏾‍💻
I'm continually adding more projects as I learn new strategies and explore new concepts, including machine learning techniques related to algorithmic trading

---

## License
This repository is open-source, so feel free to use and adapt the code for your own learning purposes.
