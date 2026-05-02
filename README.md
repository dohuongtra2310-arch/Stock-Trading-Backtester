Algorithmic Trading Backtester: SMA Crossover Strategy
📌 Project Overview
This project is a Python-based financial analysis tool designed to backtest a Simple Moving Average (SMA) Crossover strategy. It automates the process of fetching historical stock data, calculating technical indicators, simulating trades, and benchmarking performance against the traditional "Buy & Hold" approach.

🛠️ Tech Stack & Key Skills
- Language: Python
- Libraries: yfinance (Data Acquisition), pandas (Data Manipulation), plotly (Interactive Visualization).
- Quantitative Skills: Technical Analysis (SMA), Backtesting Logic, Performance Benchmarking (Alpha calculation).

🚀 Core Features
1. Automated Data Pipeline: Fetches real-time historical data from Yahoo Finance API and handles data cleaning (multi-index flattening and NaN removal).
2. Trading Strategy Implementation:
   - Golden Cross: Triggers a 'Buy' signal when the 20-day SMA crosses above the 50-day SMA.
   - Death Cross: Triggers a 'Sell' signal when the 20-day SMA crosses below the 50-day SMA.
3. Backtesting Engine: Simulates a portfolio starting with $10,000, tracking daily Net Asset Value (NAV), cash balance, and share ownership.
4. Performance Analytics: Compares the strategy's total return against a "Buy & Hold" benchmark to calculate Alpha (excess return).

📈 Results & Analysis
Using IVV.AX (S&P 500) as a test case for a 2-year period:
Strategy Return: ~29.80%
Buy & Hold Return: ~23.77%
Insight: The strategy demonstrated significant Alpha, proving the effectiveness of trend-following in volatile markets.

📂 How to Run
Clone the repository.
Install dependencies: pip install yfinance pandas plotly.
Run the script in a Python environment or Google Colab.
