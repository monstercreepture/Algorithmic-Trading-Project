Algorithmic Trading: Intraday Predictive Model
This repository contains the implementation of a predictive trading model designed to capitalize on intraday trading opportunities through optimized risk management.
Objective
The primary goal was to formulate a predictive model with optimized risk management for capitalizing on intraday trading opportunities.
Approach
The project was developed by leveraging a robust, event-driven backtesting engine to ensure realistic simulation of trading strategies.
Predictive Model: Developed a robust predictive model that leverages OHLC ratios to identify optimal intraday entry and exit points.
Risk Management: Engineered and deployed an adaptive stop-loss mechanism. The mechanism adjusts its risk threshold based on time-of-day volatility patterns, tightening during volatile periods and loosening during stable periods.
Profit Optimization: Optimized take-profit strategies by factoring in estimated investment charges (commissions and slippage) to maximize net profitability and safeguard gains.
Framework: The core backtesting engine was built using the powerful backtesting.py framework to allow for rapid iteration and statistically significant analysis.
Result
Implemented and backtested a risk-adjusted strategy over a 6-month historical data period.
The final model achieved a Sharpe Ratio of 1.39, 15% annualized returns, and a maximum drawdown of 8%.
