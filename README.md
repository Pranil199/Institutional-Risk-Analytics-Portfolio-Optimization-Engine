# Institutional-Risk-Analytics-Portfolio-Optimization-Engine
A Python-based risk management and portfolio optimization dashboard that applies Modern Portfolio Theory (MPT) to a custom basket of equities. Moving beyond basic return calculations, this engine evaluates investments strictly on **risk-adjusted performance**, calculating institutional-grade metrics like the Sortino Ratio, Value at Risk (VaR), and Maximum Drawdown. 

Additionally, it features a Monte Carlo simulation engine that generates thousands of portfolio permutations to map the Efficient Frontier and mathematically isolate the asset weighting that yields the absolute highest Sharpe Ratio.

[Image of Efficient Frontier Monte Carlo simulation for portfolio optimization]

## ✨ Core Capabilities

* **Advanced Risk Metrics:** Computes annualized volatility, Max Drawdown, and the 95% Historical Value at Risk (VaR) to quantify exact downside exposure.
* **Risk-Adjusted Return Analysis:** Calculates both the Sharpe Ratio (total volatility penalty) and the Sortino Ratio (downside-only volatility penalty) to accurately assess manager performance.
* **Asset Correlation Mapping:** Generates a dynamic Pearson correlation heatmap to visualize diversification benefits and hidden portfolio overlaps.
* **Monte Carlo Efficient Frontier:** Simulates thousands of random portfolio weightings to find the mathematically optimal allocation (Max Sharpe) under Markowitz's portfolio theory.

## 🛠️ Tech Stack & Financial Mathematics

* **Language:** Python 3.x
* **Market Data Ingestion:** `yfinance`
* **Quantitative Engine:** `numpy` (Covariance matrices, dot products, vector operations), `pandas` (Time-series rolling calculations, percentiles)

