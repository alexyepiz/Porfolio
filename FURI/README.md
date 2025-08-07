# FURI Project: Reinforcement Learning with GRU and LSTM Networks for Stock Trading

This research explores how reinforcement learning (RL) affects the performance of GRU and LSTM models for predicting stock prices and making trading decisions. It was completed as part of ASU’s Fulton Undergraduate Research Initiative (FURI).

## Summary

- **Goal:** Compare LSTM and GRU architectures with and without RL to determine which combination yields better trading performance.
- **Data:** Historical SPY data (2000–2025), with training from 2000–2015 and backtesting from 2015–2025.
- **Models:**  
  - LSTM  
  - LSTM + RL  
  - GRU  
  - GRU + RL

## Methodology

- Used a 5-day rolling window to predict next-day returns.
- RL was applied only during trading (not training) to make Buy/Sell/Hold decisions.
- Simulated with $100,000 starting capital per model.
- Performance evaluated using:  
  - Return %  
  - Win Rate  
  - Sharpe Ratio  
  - Max Drawdown

## Key Results

| Metric            | Statistically Significant (α = 0.01)? | Insight |
|-------------------|----------------------------------------|---------|
| GRU Win Rate      | ✅ Yes                                 | RL improved GRU win rate significantly |
| LSTM Return %     | ❌ No                                  | Nearly doubled, but not significant     |
| LSTM Sharpe Ratio | ❌ No                                  | Improved with RL, but didn’t meet threshold |
| GRU+RL Drawdown   | ❌ No                                  | RL introduced more volatility vs. GRU   |
| LSTM+RL Drawdown  | ❌ No                                  | Lowest drawdown across all models       |

## Conclusion

- RL benefits GRU in terms of win rate but may introduce volatility.
- LSTM+RL produced the **strongest overall performance** despite lacking statistical significance.
- Suggests RL's effectiveness may be **architecture-dependent**, with LSTM responding more stably.
- Further research should explore metrics like MSE, R², and directional accuracy.

## Files

- [📄 Poster.pdf](./FURI2_GRU-LSTM-RL_Poster.pdf) — Final FURI poster summarizing research findings

