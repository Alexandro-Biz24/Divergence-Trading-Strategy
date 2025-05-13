# Divergence-Trading-Strategy
Continuation of the psychological threshold and trend detection project. Creation and implementation of a trading strategy based on bullish and bearish divergence detection, improved by ML model to decision making.

# 📈 Algorithmic Trading on BNB/USDT (1h)

This project implements an advanced algorithmic trading framework for the **BNB/USDT** pair using 1-hour candlestick data. It combines **technical analysis**, **trend line detection**, and a **machine learning-based signal filter** to build a robust trading strategy.

---

## Features

### Technical Tools
- **Trend Line Detection** (local and global)
- **Support & Resistance Estimation**
- **Psychological Price Thresholds** (round levels)
- Interactive **Plotly** candlestick visualizations

### Algorithmic Trading Strategy
- **Divergence Detection Strategy** (e.g. price vs RSI)
- **ML-based Signal Filtering** using historical features
- Custom **Signal Scoring** system
- **Backtest engine** with PnL, risk metrics, and streak tracking

---

## 📁 Project Structure

- `BNBUSDT_1h_20171106_20250328.csv`  
  Historical OHLCV data at 1-hour frequency.

- `Project_Trend_lines.ipynb`  
  Trend detection logic, charting, scoring system.

- `Projet_algo_Trading_Bizeul.ipynb`  
  Full trading strategy implementation: divergence-based entry, ML filtering, backtesting, and evaluation.

- `/screenshots/`  
  Static previews of Plotly charts (for GitHub display).

---

##  How to Run

1. Clone the repository and open in Jupyter.
2. Install required dependencies:
  pip install numpy pandas scipy plotly scikit-learn

3. Open Projet_algo_Trading_Bizeul.ipynb and run all cells.

Note: Plotly interactive charts are commented out for GitHub compatibility. Uncomment them locally to enable full interactivity.


## Tech Stack
- Python 3.10+

- numpy, pandas, scipy

- plotly.graph_objects for advanced charting

- scikit-learn for signal verification (classification model)

- matplotlib for static summaries

## Backtest Outputs
- Win/loss statistics

- Total and average PnL

- Maximum win/loss streak

- Value-at-Risk (1% to 99%)

- Signal reason breakdown (TP / SL / EOD)

## ⚠️ Disclaimer
This project is for educational and research purposes only.
It is not financial advice and should not be used for live trading without proper validation and risk controls.
