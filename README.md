# Forex Machine Learning Pipeline (Thesis Project)

This repository contains the implementation of a thesis-level machine learning
pipeline for Forex market prediction and trading strategy evaluation.

## Models Implemented
- Random Forest (RF)
- Support Vector Machine (SVM)
- Long Short-Term Memory Network (LSTM)
- Deep Q-Network (DQN)

## Data
- Daily Forex data downloaded from Yahoo Finance
- Currency pairs:
  - EUR/USD
  - GBP/USD
  - USD/JPY
  - AUD/USD

## Features
- Log returns
- Lagged returns
- Simple Moving Averages (5, 20)
- Volatility (10-day rolling)
- RSI (14)
- MACD and MACD Signal

## Methodology
- Walk-forward (rolling window) validation
- Transaction costs modeled via bid–ask spread
- Risk-adjusted performance evaluation:
  - Sharpe Ratio
  - Maximum Drawdown
  - Cumulative Returns

## Requirements
- Python 3.9+
- See `requirements.txt`

## Usage
```bash
pip install -r requirements.txt
python forex_pipeline.py
