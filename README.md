# Fama-French 3-Factor Regression Analysis on Equity Returns (India)

## 📌 Overview
This project implements the **Fama–French 3-Factor model** for the Indian equity market, extending the standard CAPM by including **size (SMB)** and **value (HML)** factors. Using NSE equity data, survivorship-bias adjusted factor datasets were engineered, regressions estimated, and performance compared to CAPM.  

---

## 🚀 Key Features
- **Factor Dataset Construction**
  - Built India-specific **MKT–RF, SMB, HML** factors
  - Adjusted for **survivorship bias** & **corporate actions**
- **Regression Analysis**
  - OLS estimation with **Newey–West HAC errors**
  - Rolling **252-day regressions** to capture dynamic betas
  - Statistical diagnostics: **ADF, Ljung–Box, Breusch–Pagan**
- **Performance Improvements**
  - **R²** improved from **0.20–0.30 (CAPM)** to **0.35–0.55 (FF3)**
  - Significant SMB & HML loadings (**t-stat > 2**)
  - ~20% of stocks showed significant alpha
- **Portfolio Backtests**
  - Annualized return: **~12%**
  - Sharpe ratio: **1.1**
  - Max drawdown: **~15%**
  - Turnover modeling included

---
