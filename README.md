# portfolio-optimization-engine
Mean-variance, Black-Litterman, and risk parity portfolio optimization in Python with walk-forward backtesting
Compares three institutional portfolio construction methodologies across a 10-asset global ETF universe: Markowitz mean-variance, Black-Litterman, and risk parity. Each is validated through a walk-forward out-of-sample backtest from 2012 to 2026 with quarterly rebalancing, Ledoit-Wolf covariance shrinkage, and transaction cost modeling, benchmarked against equal weight.

All three optimizers are implemented from scratch using SciPy rather than a portfolio optimization library.
