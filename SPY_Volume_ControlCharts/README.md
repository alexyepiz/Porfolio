# Volatility Analysis of SPY Trading Volume

This project analyzes daily trading volume of the SPDR S&P 500 ETF (SPY) using statistical quality control methods to detect the impact of major news events on market stability.

## Summary

- **Objective:** Evaluate whether the U.S. tariff announcement on China (April 2, 2025) caused significant deviations in SPY trading volume.
- **Tools Used:** Python (yfinance, pandas), JMP Pro 18, Control Charts (X̄ and R Charts)
- **Methodology:** 
  - Collected 130 days of SPY volume data via Python.
  - Exported data to CSV and analyzed using control charts to assess statistical stability.
  - Identified multiple special cause variations, including spikes linked to market events.

## Key Findings

- SPY trading volume is not normally distributed (it is approximately lognormal).
- Multiple volume spikes were triggered by notable events (e.g., Quadruple Witching Day, Presidential Inauguration, and tariff announcement).
- Control charts confirmed the U.S.–China tariff event introduced assignable cause variation, disrupting normal trading volume patterns.

## Files

- [📄 Report.pdf](./Report.pdf) — Full analysis and control chart results
- [📓 Code.ipynb](./Code.ipynb) — Python script used to collect SPY volume data

