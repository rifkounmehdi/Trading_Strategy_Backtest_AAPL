# Trading Strategy Backtesting Project
## Project Overview

This project demonstrates a simple algorithmic trading strategy using Python. The strategy is based on a moving average crossover applied to **Apple (AAPL)** stock, with buy/sell signals generated from short-term and long-term moving averages.

* Download historical stock data using `yfinance`.
* Calculate short-term (10-day) and long-term (50-day) moving averages.
* Generate buy/sell signals based on moving average crossovers.
* Backtest strategy performance against a buy & hold benchmark.
* Visualize cumulative returns and trade signals using `matplotlib`.

## How to Run

1. Install required packages:

```bash
pip install pandas numpy matplotlib yfinance
```

2. Run the Jupyter Notebook (`.ipynb`) to see the backtest and visualizations.

