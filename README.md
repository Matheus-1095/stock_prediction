# 📈 Stock Prediction with Machine Learning

## Objective
This project aims to build a **machine-learning–based quantitative trading strategy**
focused on **risk control**, **positive expected value**, and **out-of-sample evaluation**,
rather than naive price prediction.

## Approach
- Time-series feature engineering (returns, volatility, trends, liquidity)
- Temporal train-test split (no data leakage)
- LSTM neural network trained as a probabilistic classifier
- Dynamic threshold based on probability quantiles
- Backtest with realistic evaluation metrics

## Metrics Used
- Sharpe Ratio
- Hit Ratio (accuracy per trade)
- Expected Value (mathematical expectation)
- Cumulative Return
- Drawdown

## Results
- Sharpe Ratio ≈ 1.0 (out-of-sample)
- Positive mathematical expectation per trade
- Conservative exposure with controlled drawdowns

## Limitations
- Single asset (VALE3)
- No transaction costs
- Single historical period

## Next Steps
- Walk-forward validation
- Ensemble models
- Transaction cost modeling
- Cross-asset features
