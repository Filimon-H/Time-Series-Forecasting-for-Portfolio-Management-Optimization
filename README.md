# Time Series Forecasting for Portfolio Management Optimization

## Overview
This project applies time series forecasting to historical financial data to enhance portfolio management strategies for GMF Investments.

## Assets Analyzed
- **TSLA** (Tesla): High-growth stock, high risk/return
- **BND** (Vanguard Total Bond Market ETF): Low risk, stability
- **SPY** (S&P 500 ETF): Moderate risk, broad market exposure

## Project Structure
```
├── data/processed/       # Cleaned datasets
├── notebooks/            # Jupyter notebooks for analysis
├── src/                  # Source code modules
├── scripts/              # Utility scripts
├── tests/                # Unit tests
└── requirements.txt      # Python dependencies
```

## Setup
```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Tasks
1. **Data Preprocessing & EDA** - Load, clean, explore data
2. **Time Series Forecasting** - ARIMA/SARIMA + LSTM models
3. **Future Trend Forecasting** - Generate predictions with confidence intervals
4. **Portfolio Optimization** - Efficient Frontier using MPT
5. **Strategy Backtesting** - Validate strategy vs benchmark
