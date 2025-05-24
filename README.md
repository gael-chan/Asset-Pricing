# Asset-Pricing

## Key Concepts

### Overview
This repository contains the code and documentation for the project of Asset Pricing under MSc Quantitative Finance at Bayes Business School (formerly CASAS).

---

## Key Concepts by Task

### Task 1: Forecasting Model and Market Timing
- **EGARCH Model**: Applied to forecast UK stock market volatility.
- **Decision Rule**: Invest in equities if predicted return > 1-month UK government bond yield; otherwise, allocate to risk-free asset.
- **Investment Frequency**: Semi-annual decisions from Oct 2014 to Apr 2024.
- **Macroeconomic Factors**:
  - Lagged Nasdaq returns for global sentiment.
  - UK M2 supply and interest rate interaction to capture liquidity.

---

### Task 2: Portfolio Construction
- **Efficient Frontier Calculation**:
  - Conducted semi-annually using historical return/covariance matrices.
  - Derives both **Minimum Variance** and **Market (Optimum)** Portfolios.
- **Stock Selection**:
  - 5 UK equities chosen based on diversification and Sharpe ratio.
- **Capital Allocation Line (CAL)**:
  - Customisable client portfolios via bond and equity blend.

---

### Task 3: Strategy Backtesting and Terminal Wealth
- **Portfolios Analysed**:
  1. Market Portfolio (No Rebalancing)
  2. Market Portfolio (Semi-Annual Rebalancing)
  3. Minimum Variance Portfolio (No Rebalancing)
  4. Minimum Variance Portfolio (Semi-Annual Rebalancing)
  5. FTSE All Share Index
  6. Risk-Free Bond
  7. Forecasting Model-Guided Portfolio
- **Result**:
  - **Forecasting Model-Guided Portfolio** achieved highest CAGR: **4.12%**

---

### Task 4: Client-Focused Insights
- **Recommendation**:
  - Combine EGARCH forecasting with mean-variance optimisation.
  - Use Minimum Variance Portfolio for stable long-term growth.
- **Caution**:
  - Mean-variance output is sensitive to expected return estimates.
  - Inaccurate inputs may cause over-concentration and increased risk.

---

## 🛠️ Tools & Methods Used
- Python (Jupyter Notebook)
- NumPy, Pandas, Matplotlib, Statsmodels
- GARCH-family models
- Markowitz Mean-Variance Optimisation

---

## 📁 Repository Structure
- `DataAnalysis_EfficientFrontiers.ipynb` – Core code for analysis and optimisation
- `Client-Facing-Report.pdf` – Summarised investor report
- `Task.pdf` – Assignment brief
- `Data` - Dataset used for the tasks
---
