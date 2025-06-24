# Portfolio Hedging and Performance Analysis

## 📊 Project Overview

This project analyzes a portfolio of 8 stocks compared to the NIFTY index over the past 6 months. It covers return analysis, beta exposure, volatility, hedging using futures, and portfolio performance using different weighting strategies.

---

## 📁 Data Used

- **Book3.csv**: Contains daily returns of 8 stocks and NIFTY, and final row includes beta values.
- **Portfolio_Returns.csv**: Daily return data used for portfolio construction.

---

## 🔍 Methods

1. **Investment-Weighted Portfolio**  
   - Weights based on ₹ invested in each stock.
   - Compared return and risk with NIFTY.

2. **Beta-Weighted Portfolio**  
   - Weights based on each stock’s beta relative to total beta.
   - Used to assess risk-adjusted performance and hedging.

3. **Beta Calculation**  
   - Used slope of regression line (stock returns vs NIFTY) to compute individual betas.

4. **Hedging Using NIFTY Futures**  
   - Calculated hedge value as:  
     `Hedge = Portfolio Value × Portfolio Beta`
   - Number of contracts = Hedge Value / (NIFTY Level × Lot Size)

5. **Performance Metrics Computed**  
   - Average Daily Return  
   - Annual Return  
   - Annual Volatility  
   - Sharpe Ratio (risk-adjusted return)

6. **Cumulative Return Plots**  
   - Visualized performance of NIFTY, Investment Portfolio, and Beta-Weighted Portfolio over time.

---

## 📈 Final Output

Includes:
- Summary table of all metrics (return, volatility, Sharpe ratio)
- Cumulative return comparison plot
- Hedging exposure plot

---

## 📌 Tools Used

- Python (pandas, matplotlib, numpy)
- Google Colab
- CSV Files for input data
