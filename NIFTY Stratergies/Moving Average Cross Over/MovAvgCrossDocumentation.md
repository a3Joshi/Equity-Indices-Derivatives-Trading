# Moving Average Crossover Strategy for NIFTY 50 ETFs
## Overview
This project implements a Moving Average Crossover trading strategy on NIFTY 50 ETFs using historical data fetched with yfinance. It is designed to demonstrate the application of this simple yet powerful technical analysis strategy in the Python programming environment.The script performs the following operations:

Fetches historical price data for a NIFTY 50 tracking ETF from Yahoo Finance.
Computes short-term and long-term moving averages.
Generates buy and sell signals based on the crossover of these moving averages.
Backtests the strategy to display performance metrics and plots the results.
Strategy Details
Short Moving Average (SMA): Fast moving average calculated over a short window (default is 50 days).
Long Moving Average (LMA): Slow moving average calculated over a long window (default is 200 days).
Signals:

Buy Signal: Generated when SMA crosses above LMA.
Sell Signal: Generated when SMA crosses below LMA.
Backtesting
The strategy is backtested using historical data:

Market Returns: Logarithmic returns of the ETF.
Strategy Returns: Returns of the strategy based on trading signals.
Cumulative Returns: The cumulative returns of both the market and the strategy are plotted for comparison.
Contributing
Contributions to this project are welcome. You can contribute in several ways:

Enhancing the strategy logic.
Improving the backtesting framework.
Adding new features or fixing bugs.
Please fork the repository and submit pull requests with your changes.
