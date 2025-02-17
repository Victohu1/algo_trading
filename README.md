# Algo Trading Bot

## Overview
This project is an **algorithmic trading bot** that takes **live stock market data** and predicts stock prices for the next X period of time using ML models.

The original code for `trading_bot` and `finbert_utils.py` is credited to **Nicholas Renotte** from Youtube. Subsequent modifications are mine.

---
## Environment: algo_trading

Install the environment: pip install -r requirements.txt

Activating the virtual envrionment: algo_trading\Scripts\Activate.ps1

If there is an permission error, change the execution policy with: Set-ExecutionPolicy Unrestricted -Scope Process

---
## Project Structure
algo_trading/
│── strategies/                # Trading strategy modules
│   ├── ML_models/             # Machine learning models
│   ├── stats_models/          # Statistic based models
│── tradingbot/                # Trading bot implementation
│   ├── notebooks/             # Jupyter notebooks for testing
│   │   ├── trading_bot.ipynb  # Trading bot design notebook
|   |── trading_bot.py         # Trading bot
│── requirements.txt           # Project dependencies
│── README.md                  # Project documentation