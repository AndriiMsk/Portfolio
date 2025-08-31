# 📈 Portfolio Optimization with Markowitz Theory

This project implements a **Markowitz portfolio optimization** using Python.  
We simulate random portfolios, calculate expected returns, volatilities, Sharpe ratios,  
and visualize the efficient frontier along with other insights.

---

## 1. Overview
- **Data:** Daily stock prices of AAPL, TSLA, MSFT  
- **Methods:**
  - Daily returns, covariance & correlation matrices  
  - Monte Carlo simulation of 5000 random portfolios  
  - Identification of:
    - Minimum Volatility Portfolio ⭐
    - Maximum Sharpe Ratio Portfolio ⭐  
- **Visualizations:**
  - Efficient frontier with highlighted optimal portfolios  
  - Correlation heatmap of daily returns  
  - Cumulative returns (normalized to 1)  
  - Rolling 21-day volatility (annualized)  

---

## 2. Results

### Efficient Frontier
Red ⭐ = Minimum Volatility, Yellow ⭐ = Maximum Sharpe  
![Efficient Frontier](images/efficient_frontier.png)

### Correlation Heatmap
![Correlation Heatmap](images/correlation_heatmap.png)

### Cumulative Returns
![Cumulative Returns](images/cumulative_returns.png)

### Rolling Volatility
![Rolling Volatility](images/rolling_volatility.png)

---

## 3. Requirements
```bash
pip install pandas numpy matplotlib seaborn

---

## 4. Next Steps

    Extend with more assets (AMZN, NVDA, JPM, etc.)

    Use longer historical data (5–10 years) for stability

    Compare against benchmark (e.g., S&P 500 ETF)

---

## 5. Author

Project prepared as a practice case for quantitative finance & data analysis portfolio.

---