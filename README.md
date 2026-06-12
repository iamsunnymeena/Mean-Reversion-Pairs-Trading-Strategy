# Statistical Mean Reversion Pairs Trading Strategy

## Overview
This project implements a market-neutral pairs trading framework based on statistical arbitrage and mean reversion principles. The objective is to identify highly correlated and cointegrated equity pairs, model the spread between them, and generate trading signals when deviations from historical equilibrium become significant.

## Features
- Cointegration-based pair selection
- Spread modelling and z-score analysis
- Linear Regression, Kalman Filter, and ARIMA approaches
- Historical backtesting workflow
- Performance evaluation using Sharpe, Sortino, Calmar ratios and drawdowns
- Alpaca paper-trading integration

## Project Workflow
1. Collect historical market data.
2. Identify candidate pairs with strong statistical relationships.
3. Estimate the spread and its mean-reverting behaviour.
4. Generate entry and exit signals using predefined thresholds.
5. Backtest the strategy and evaluate risk-adjusted returns.
6. Deploy for paper trading through Alpaca.

## Technology Stack
- Python
- Pandas
- NumPy
- Statsmodels
- yFinance
- Alpaca API

## Repository Structure
- `data/` : Datasets and pair-selection results
- `strats/` : Research notebooks and strategy development
- `broker/` : Paper-trading deployment scripts
- `image/` : Performance and result visualizations

## Author
Sunny Meena

## Disclaimer
This repository is intended for educational and research purposes only. It should not be considered financial advice or a recommendation to trade any security.
