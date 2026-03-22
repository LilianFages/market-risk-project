# Market Risk Project

This repository contains the final PDF report for the **Market Risk Project** completed at **ESILV** during the **2025–2026 academic year**.

## Authors
- Lilian Fages
- Nel Choisnet Dupuij

## Supervisor
- LEFEVRE Cassandre

## File
- `market_risk_eng.pdf` — final written report of the project

## Project overview

This report applies the main tools introduced in the **Market Risk** course to real financial datasets. It focuses on one-day market risk measurement, tail-risk modeling, liquidity effects, and multiscale dependence. The project combines both statistical and economic interpretations, moving from non-parametric risk estimation to extreme-value methods and market microstructure analysis.

## Main topics covered

The report is structured around several questions and covers the following topics:

- **Historical non-parametric VaR** using a **biweight-kernel KDE**
- **Out-of-sample VaR backtesting** over 2017–2018, including exceedance analysis and Kupiec coverage diagnostics
- **Expected Shortfall (ES)** and comparison with VaR
- **Extreme Value Theory (EVT)** with **Pickands tail-index estimation**
- **EVT-based VaR extrapolation** for extreme losses
- **Bouchaud’s price impact model**, including estimation of transient price impact and volume dependence
- **Multiresolution correlations** based on **Haar wavelets**
- Analysis of the **Epps effect**
- **Hurst exponent estimation** and **annualized volatility scaling** beyond the Brownian benchmark

## Report structure

The document contains:

1. **Introduction**
2. **Questions and Answers**
   - Question A: non-parametric VaR and backtesting
   - Question B: Expected Shortfall
   - Question C: EVT and Pickands estimation
   - Question D: Bouchaud price impact model
   - Question E(a): multiresolution correlations and Epps effect
   - Question E(b): Hurst exponents and annualized volatilities
3. **Conclusion**

## Key takeaway

A central conclusion of the report is that **no single method is sufficient for a comprehensive market risk assessment**. The project shows that non-parametric VaR, Expected Shortfall, EVT-based tail modeling, liquidity analysis, and multiscale methods all provide complementary information and should be combined for a more robust view of financial risk.

## Repository purpose

This repository is intended to provide direct access to the final PDF version of the project report in a simple and shareable format.
