# Bull Call Spread Options Tool

This project provides a Python-based tool to calculate the profit and loss characteristics of a bull call spread — a widely used options trading strategy.

## Summary

- **Strategy:** A bull call spread involves buying a call option at a lower strike price and selling another call at a higher strike price, both with the same expiration.
- **Goal:** Build an interactive tool to analyze potential outcomes, including breakeven, max profit/loss, and return metrics.
- **Tools Used:** Python, Jupyter Notebook, Financial Modeling

## Inputs (User-Defined)

- Strike Price of Long Call (Low Strike)
- Premium Paid for Long Call
- Implied Volatility for Long Call (IV1)
- Strike Price of Short Call (High Strike)
- Premium Received for Short Call
- Implied Volatility for Short Call (IV2)
- Stock Price
- Days til Expiration
- Risk Free Rate

## Outputs (Calculated)

- Breakeven Price
- Breakeven % Move
- Maximum Profit (per contract)
- Maximum Loss (per contract)
- Risk to Reward
- Low Strike Probability of Profit (Low POP)
- Breakeven Price Probability of Profit (Breakeven POP)
- High Strike Price Probability of Profit (High POP)
- High Strike Black-Scholes
- Low Strike Black-Scholes
- Leverage

## Use Case

This tool is ideal for students, traders, or finance professionals who want to analyze the risk/reward profile of a bull call spread and better understand option strategy outcomes before entering a position.

## File

- [📓 Bull_Call_Spread_Tool.ipynb](./Bull_Call_Spread_Tool.ipynb)


