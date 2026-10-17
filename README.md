# Bitcoin Regime-Aware Trading Strategy

## Project Overview

This project investigates whether identifying different Bitcoin market regimes can help inform the design of a systematic trading strategy.

Bitcoin markets can exhibit different behavior across periods, including changes in returns, volatility, and market direction. The goal is to explore how market conditions can be analyzed and incorporated into a structured, data-driven trading approach.

## Objectives

- Retrieve and analyze historical Bitcoin market data.
- Explore return behavior and volatility across different market conditions.
- Investigate methods for identifying market regimes.
- Develop a framework for evaluating a regime-aware trading strategy.
- Assess strategy performance against an appropriate benchmark, accounting for risk and transaction costs where applicable.

## Technologies

- Python 3.11
- Pandas
- NumPy
- yfinance
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Structure

- `bitcoin_regime_aware_trading_strategy.ipynb` — main research notebook.
- `PROJECT.md` — project objectives and planning documentation.
- `requirements.txt` — Python dependencies.
- `.gitignore` — files and directories excluded from version control.

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/laperezortiz/bitcoin-regime-aware-trading-strategy.git
cd bitcoin-regime-aware-trading-strategy
```

### 2. Create and activate a virtual environment

On macOS or Linux:

```bash
python3.11 -m venv .venv
source .venv/bin/activate
```

### 3. Install dependencies

```bash
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

### 4. Launch Jupyter

```bash
jupyter notebook
```

Open `bitcoin_regime_aware_trading_strategy.ipynb` and run the notebook cells in order.

## Evaluation

The strategy should be evaluated using appropriate performance and risk measures. Potential measures include cumulative return, maximum drawdown, volatility, and risk-adjusted performance.

Results, visualizations, and conclusions will be documented here after the analysis and backtesting have been completed.

## Limitations

Historical market behavior does not guarantee future performance. Backtests can be affected by data quality, look-ahead bias, overfitting, transaction costs, and execution assumptions. Any conclusions should be interpreted in light of these limitations.

## Disclaimer

This project is for educational and research purposes only. It does not constitute financial or investment advice.
