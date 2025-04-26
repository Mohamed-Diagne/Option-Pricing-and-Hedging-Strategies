# 📈 Advanced Option Pricing and Hedging Strategies: Black-Scholes, Monte Carlo, Local Volatility, and Greeks Analysis

## 📚 Overview
This project explores **option valuation** and **risk management** strategies applied to **Puig's IPO stock**, using models such as **Black-Scholes**, **Monte Carlo simulations**, **Binomial Trees**, and **Local Volatility** modeling.  
We combine theory and practice to hedge risks dynamically (Delta, Gamma, Vega, Theta).

---

## 🎯 Objectives
- Price options using **Black-Scholes** and **Monte Carlo** under constant and local volatility.
- Analyze **Greeks** (Delta, Gamma, Vega, Theta) to understand sensitivity.
- Implement **protective put**, **gamma**, **vega**, and **theta-neutral** hedging.
- Extend valuation to **binomial trees** for American options.
- Compare theoretical vs market-implied volatilities (IV estimation).
- Understand stochastic processes behind asset price dynamics.

---

## 🛠 Methodologies Implemented
**Option Pricing:**
- Black-Scholes closed-form formula.
- Monte Carlo simulation under **risk-neutral measure** (GBM).
- Local Volatility surface approximation (Dupire formula).
- Binomial tree model for American options.

**Risk Management via Greeks:**
- Delta, Gamma, Vega, Theta calculation and interpretation.
- Dynamic Delta-Gamma neutral rebalancing.
- Vega neutralization strategies (call spreads).
- Theta-neutral butterfly spread construction.

**Hedging Strategies:**
- **Protective Put**.
- **Gamma Neutral** using short calls.
- **Vega Neutral** by option spread adjustment.
- **Theta Hedging** via butterfly and hedge positions.

**Stochastic Processes:**
- Standard and Geometric Brownian Motion (GBM) modeling.
- Interpretation of volatility smiles and skews via local volatility.

---

## 📚 Data Sources
- **Stock Data**: Puig (ticker `PUIG.MC`) from Yahoo Finance.
- **Risk-Free Rate**: 3-Month EURIBOR.
- **Volatility Estimation**: Historical log-returns SMA method.

---

## 📈 Key Results
- Black-Scholes European call valued at **€0.83**, put at **€1.27**.
- Monte Carlo call price estimated at **€0.8156** (CI: €0.7881–€0.8430).
- Local volatility lower than implied volatility, reflecting **market skew**.
- Hedging strategies demonstrated effective risk neutralization (Delta, Gamma, Vega, Theta).
- American option value exceeds European value due to early exercise premium.

---

## 🚀 How to Run
1. Clone the repository.
2. Install dependencies:
```bash
pip install -r requirements.txt
```

---

## 🔮 Future Improvements
* Implement stochastic volatility models (e.g., Heston model).
* Extend local volatility surface estimation to full strike/maturity grids.
* Model jumps and discontinuities using Merton jump diffusion processes.

---

## 📖 References
* Black, F., & Scholes, M. (1973). The Pricing of Options and Corporate Liabilities. Journal of Political Economy.
* Alexander, C. (2008). Market Risk Analysis, Volume I: Quantitative Methods in Finance. Wiley.
* Shreve, S. E. (2004). Stochastic Calculus for Finance II. Springer Finance.
* Le Moign, C., & Ezra, A. (2021). Caractéristiques du marché des options sur actions françaises. AMF.
* Petrov, D. (2025). Risk Management Course Notes.
---

## 📑 License
This project is for educational purposes only.


