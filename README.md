# Hedge Fund Portfolio Optimization and Industry Momentum Analysis

## Project Overview

This project focuses on two key areas of financial analytics: optimizing hedge fund portfolio allocation to maximize the Sharpe ratio and backtesting an industry momentum equity strategy. The analysis was conducted using Python and Excel, providing a comprehensive examination of return dynamics, portfolio performance, and risk management.

## Objectives

1. **Hedge Fund Portfolio Optimization**: 
   - Analyze a multi-strategy hedge fund with the goal of optimizing portfolio allocation across nine trading strategies.
   - Compare the performance of an equal-weighted portfolio versus an optimized portfolio using the Sharpe ratio.
   - Evaluate the portfolio's performance across different time periods to determine the robustness of the optimal allocation.

2. **Industry Momentum Strategy Backtesting**: 
   - Implement and backtest an industry momentum strategy, which involves buying industries with rising momentum and shorting those in decline.
   - Calculate and analyze the returns, volatility, and Sharpe ratio of both "winner" and "loser" portfolios.
   - Develop a long-short portfolio and assess its risk-adjusted performance against the market.

## Key Components

### 1. Hedge Fund Portfolio Optimization

#### Tasks:
- **Excess Return Calculation**: Compute the excess return for each hedge fund index.
- **Equal-Weighted Portfolio**: Create a portfolio with equal weights (1/9) for each strategy and calculate the portfolio’s return, volatility, and Sharpe ratio across two sample periods: 1994-2003 and 2004-2012.
- **Sharpe Ratio Optimization**: Determine the optimal portfolio weights to maximize the Sharpe ratio during the 1994-2003 period and compare it to the equal-weighted portfolio.
- **Out-of-Sample Testing**: Apply the optimal weights to the 2004-2012 period to assess the out-of-sample performance.
- **Full Sample Analysis**: Compare the overall portfolio performance across the entire time period using both equal and optimized weights.
- **Capital Allocation Decision**: Based on the analysis, decide whether to allocate capital using an equal-weighted or optimized portfolio.

### 2. Industry Momentum Strategy Backtesting

#### Tasks:
- **Momentum Calculation**: Calculate the 12-month trailing average return for each industry and rank the industries accordingly.
- **Winner and Loser Portfolios**: Identify the top 15 (winner) and bottom 15 (loser) industries based on their past performance and calculate their respective portfolio returns.
- **Long-Short Portfolio Construction**: Create a long-short portfolio by going long on the winner industries and short on the loser industries, and analyze its performance.
- **Sharpe Ratio and Risk Metrics**: Compute the Sharpe ratio, alpha, beta, and t-statistics for the long-short strategy and compare it to the overall market.
- **Cumulative Return Analysis**: Plot the cumulative returns of the winner, loser, long-short portfolios, and the market over the entire sample period.
- **Loss Analysis**: Investigate significant losses in the industry momentum strategy, particularly during the financial crisis in 2009, and compare it to market performance.

## Tools and Technologies Used

- **Python**: Utilized for performing financial analysis, optimization, and backtesting strategies.
- **Excel**: Employed for data processing, ranking industries, and calculating returns, with detailed documentation of the calculations.
- **Financial Metrics**: Focused on Sharpe ratio, volatility, alpha, beta, and cumulative returns to assess the performance and risk of the strategies.

## Conclusion

This project provides a comprehensive analysis of hedge fund portfolio optimization and industry momentum strategies. By leveraging Python and Excel, the project explores the trade-offs between risk and return in portfolio management, offering valuable insights into the effectiveness of different allocation strategies. The findings contribute to a deeper understanding of how to manage and optimize financial portfolios in a real-world setting.

![image](https://github.com/user-attachments/assets/90451fc3-8f59-40b8-b32d-493079c927b4)
