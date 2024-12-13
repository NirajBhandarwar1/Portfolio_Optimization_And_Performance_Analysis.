
# Portfolio Optimization and Performance Analysis


## Overview
This project focuses on building and analyzing investment portfolios using S&P 500 stocks with a specific focus on AAPL, TSLA, DIS, and AMD. The analysis involves comparing the performance of an Equal-Weighted Portfolio (EWP) and a Markowitz Mean-Variance (MMV) optimized portfolio. Key metrics such as cumulative return, CAGR, Sharpe ratio, and Maximum Drawdown (MDD) were calculated using QuantStats and PyPortfolioOpt, demonstrating improved performance with the MMV approach.

## Key Highlights
- Portfolio Construction:
  - Built an Equal-Weighted Portfolio (EWP) with equal allocation across stocks.
  - Implemented the Markowitz Mean-Variance (MMV) Model to optimize the portfolio for maximum risk-adjusted returns.
- Performance Metrics:
  - Cumulative Return: 3429% for EWP and 4830% for MMV.
  - CAGR: Achieved 32.6% for EWP and 36.2% for MMV.
  - Sharpe Ratio: 1.08 for EWP and 1.17 for MMV.
  - Maximum Drawdown (MDD): -52.2% for EWP, reduced to -45.9% with MMV.
- Tools Used:
  - QuantStats: For performance analysis and visualization.
  - PyPortfolioOpt: To implement the Mean-Variance Optimization model.
- Analysis and Insights:
  - Compared EWP and MMV portfolios in terms of returns, volatility, and risk-adjusted performance.
  - Demonstrated how optimization techniques like MMV can improve portfolio performance.

##  Dependencies
Install the following Python libraries to run this project:

- pandas
- numpy
- yfinance
- matplotlib
- pyportfolioopt
- quantstats
- seaborn
## Methodology
- Data Collection:
  - Retrieved S&P 500 stock data from Yahoo Finance for the selected stocks (AAPL, TSLA, DIS, AMD) using the yfinance library.
- Portfolio Construction:
  - Equal-Weighted Portfolio (EWP): Allocated equal weights to each stock in the portfolio.
  - Markowitz Mean-Variance Optimization (MMV):
    - Used PyPortfolioOpt to compute the efficient frontier.
    - Maximized the Sharpe ratio to create an optimized portfolio.
- Performance Analysis:
  - Used QuantStats to compute key performance metrics: CAGR, cumulative return, Sharpe ratio, and MDD.
  - Analyzed risk-return trade-offs between EWP and MMV.
- Visualization:
  - Created interactive charts for portfolio performance over time.
  - Visualized the efficient frontier and asset weights in the MMV portfolio.
## Results
- Equal-Weighted Portfolio (EWP):
  - Cumulative Return: 3429%
  - CAGR: 32.6%
  - Sharpe Ratio: 1.08
  - Maximum Drawdown (MDD): -52.2%
- Markowitz Mean-Variance Portfolio (MMV):
  - Cumulative Return: 4830%
  - CAGR: 36.2%
  - Sharpe Ratio: 1.17
  - Maximum Drawdown (MDD): -45.9%
- Insights:
  - The MMV model outperformed the EWP in all key performance metrics.
  - Risk-adjusted returns were significantly improved with MMV optimization.
  - Maximum Drawdown was reduced in the MMV portfolio, indicating better risk management.
## Conclusion
This project demonstrates how portfolio optimization techniques like the Markowitz Mean-Variance Model can enhance portfolio performance compared to simpler allocation strategies like an Equal-Weighted Portfolio. By combining QuantStats for performance evaluation and PyPortfolioOpt for optimization, we achieved higher returns and better risk management.
## Future Improvements

- Dynamic Portfolio Rebalancing: Implement periodic rebalancing to maintain optimal weights over time.
- Incorporate Transaction Costs: Account for transaction costs in the performance analysis.
- Expand Portfolio Universe: Analyze portfolios with a broader selection of S&P 500 stocks.
