# Advanced Asset Management & Sustainable Finance  
**Academic Year:** 2024–2025  
**Course:** Advanced Asset Management & Sustainable Finance  by Professor Thierry Roncalli

---

## Overview  
This repository contains the complete solution to the final project for the course *Advanced Asset Management & Sustainable Finance*. The project is divided into two main exercises focusing on:

- Mean-Variance Optimization and Portfolio Theory  
- Sustainable Investment and Climate-Constrained Portfolios

The goal was to apply quantitative methods to construct and analyze investment portfolios under various risk, return, and sustainability constraints.

---

## Exercise 1: Portfolio Optimization  

### Topics Covered
- CAPM: Expected returns, covariance, volatility, Sharpe ratio  
- Mean-Variance Optimization with different constraints:
  - Long-short
  - Long-only
  - With and without a risk-free asset
- Efficient Frontier computation and visualization  
- Tangency Portfolio: Analytical vs Brute-Force  
- Risk Metrics: Beta, Alpha, Marginal Risk (MR), Risk Contribution (RC), Percentage RC (RC*)  
- Diversification Ratio and Most Diversified Portfolio  
- Equal Risk Contribution (ERC) Portfolio

### Tools Used
- `cvxopt` for quadratic programming  
- Matrix algebra and numerical optimization in Python

---

## Exercise 2: Sustainable Portfolio Construction  

### ESG and Climate Metrics
- Carbon Intensity (CI)  
- Carbon Momentum (CM)  
- Green Intensity (GI)  
- ESG Score (S)

### Optimization Features
- Benchmark tracking under carbon reduction constraints  
- Time-dependent CI reduction modeling  
- Sectoral decomposition and exposure control  
- Multi-constraint optimization: CI, GI, CM, S  
- Sector-neutral and sector-constrained portfolios

### Advanced Constraints
- Dynamic tightening of CI constraint over time  
- Simultaneous climate and ESG constraints  
- Sector-based conditional carbon intensity limits

### Tools Used
- `cvxpy` for flexible quadratic programming  
- Custom Python scripts for metric evolution, visualization, and diagnostics

---

## Key Findings
- The Sharpe ratio remains constant along the positive segment of the efficient frontier when including a risk-free asset, validating the Two-Fund Separation Theorem.  
- Long-only portfolios show reduced diversification compared to long-short, but still perform competitively under proper allocation.  
- Carbon constraints can be enforced with minimal tracking error impact over short horizons.  
- Multi-constraint optimization enhances sustainability but increases deviation from the benchmark.

---

## References
- Markowitz, H. (1952). *Portfolio Selection*.  
- Sharpe, W. F. (1964). *Capital Asset Prices: A Theory of Market Equilibrium*.  
- Modern Portfolio Theory and Sustainable Investing literature
- Professor Thierry Roncalli Lecture Notes

---

## Authors
- Flavio Salvatore Boccia  
- Ludovico Costa

---

## License
This project is developed for academic purposes and does not constitute financial advice.  
All content © 2025 by the authors.
