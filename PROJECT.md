# Technology Project — Bitcoin Regime-Aware Trading Strategy

## 1. GENERAL INFORMATION

- **Project name:** Technology Project — Bitcoin Regime-Aware Trading Strategy
- **Specialization:** Data Science (DS)
- **Source:** Historical Bitcoin market data from Yahoo Finance
- **Original source:** https://finance.yahoo.com/quote/BTC-USD/history/
- **Published project:** To be added after publication on GitHub

## 2. OBJECTIVE

This project investigates whether identifying different Bitcoin market regimes can help improve a simple trading strategy. Using historical market data and machine learning, the project will compare a regime-aware strategy against a buy-and-hold benchmark, accounting for risk, transaction costs, and the limitations of historical backtesting.

## 3. WORK PLAN

### Step 1: Initial Exploration
- Obtain historical Bitcoin daily price and volume data.
- Inspect data quality, missing values, date coverage, and price movements.
- Explore daily returns, rolling volatility, and drawdowns.

### Step 2: Data Preparation and Feature Engineering
- Calculate daily returns and rolling market indicators.
- Create features that describe recent market conditions.
- Avoid look-ahead bias by ensuring that trading decisions use only information available at the time.

### Step 3: Market Regime Identification and Strategy Construction
- Use K-Means clustering to identify distinct market regimes based on return and volatility features.
- Interpret the resulting clusters using their statistical characteristics.
- Construct a simple trading strategy that adjusts market exposure according to the identified regimes.

### Step 4: Backtesting and Evaluation
- Evaluate the strategy using chronological data and a clearly separated testing period.
- Compare its performance with a buy-and-hold benchmark.
- Calculate cumulative return, annualized volatility, maximum drawdown, and Sharpe ratio.
- Account for reasonable transaction costs and compare results before and after costs.

### Step 5: Conclusions and Next Steps
- Interpret the financial and statistical results.
- Discuss the limitations of the model and backtesting methodology.
- Identify improvements that could be explored with more time or data.

## 4. KEY QUESTIONS

1. Do the identified market regimes exhibit meaningfully different return and volatility characteristics?
2. Does the regime-aware strategy improve risk-adjusted performance or reduce drawdowns relative to buy-and-hold on unseen data?
3. Do the results remain useful after transaction costs, and how sensitive are they to the strategy's assumptions?

## 5. WHAT WAS DONE AND HOW

To be completed during the project. Document the actual data-cleaning decisions, feature transformations, clustering settings, strategy rules, testing methodology, and transaction-cost assumptions.

## 6. RESULTS

To be completed after the backtest. Report the final test-period metrics, compare the strategy with buy-and-hold, and explain whether the evidence supports the research hypothesis.

## 7. CONCLUSIONS

To be completed at the end. Summarize the main findings, what was learned, the limitations of the analysis, and the improvements that would be most valuable in a future iteration.

## 8. CHECKLIST BEFORE PUBLISHING

- [ ] README explains the project without requiring readers to inspect every detail.
- [ ] Files are organized and outdated or temporary files are excluded.
- [ ] No credentials or sensitive data are included in the repository.
- [ ] The original data source is linked and accessible.
- [ ] The project is published and accessible on GitHub.
- [ ] The GitHub link has been shared with the coach.
