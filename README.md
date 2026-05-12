# Equity Factor Research: Momentum and Volatility

This project analyzes momentum and volatility factors in equity markets using Python.

The goal is to explore whether simple factor signals can help explain future stock returns.

## Project Overview

In this notebook, I calculate momentum and volatility-based factors for selected stocks and compare their relationship with future returns.

The project includes:

- Historical stock price analysis
- Daily return calculation
- Momentum factor calculation
- Volatility factor calculation
- Future return analysis
- Quantile-based factor comparison
- Information coefficient analysis

## Factors Used

- 20-day momentum
- 60-day momentum
- 20-day volatility
- 60-day volatility

## Target Variable

- 20-day future return

## Methodology

The workflow follows these steps:

1. Collect and prepare equity price data
2. Calculate daily returns
3. Create momentum and volatility factors
4. Calculate future 20-day returns
5. Rank observations into factor quantiles
6. Compare future returns across quantile groups
7. Calculate Q5-Q1 factor spreads
8. Evaluate factor quality using information coefficient analysis

## Tools and Libraries

- Python
- pandas
- numpy
- matplotlib
- yfinance

## Key Idea

Factor research is not about predicting stock prices directly.

Instead, it tries to test whether certain characteristics, such as momentum or volatility, are related to future returns.

## Limitations

This project is for research and educational purposes only.

Limitations include:

- Limited stock universe
- Open-source market data
- Possible survivorship bias
- No transaction cost modeling
- No live trading system
- No investment advice

## Next Steps

Possible improvements:

- Expand the stock universe
- Add benchmark comparison
- Convert factor signals into a backtested portfolio strategy
- Include transaction costs
- Test long-only and long-short strategies
- Add walk-forward validation

## Disclaimer

This project is for educational and research purposes only.  
It is not financial advice.
