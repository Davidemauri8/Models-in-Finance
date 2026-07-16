# Models-in-Finance

# Advanced Mathematical Models in Finance

Implementation of two quantitative finance projects developed for the **Advanced Mathematical Models in Finance** course.

The repository contains numerical models, analytical derivations, and Python implementations for insurance pricing and structured derivatives valuation using stochastic modeling and Monte Carlo simulation.

---

## Project Overview

The repository is divided into two independent projects.

### Project A — Parametric vs Classical Insurance

This project compares two insurance mechanisms:

- Classical indemnity insurance
- Parametric insurance

using a **Mean-Variance (MV)** decision framework.

The analysis models flood losses as a compound Poisson process with censored exponential severities and investigates when a parametric insurance contract becomes preferable to a traditional indemnity contract.

Main topics include:

- Compound Poisson loss model
- Censored exponential severity distribution
- Mean-Variance utility
- Optimal deductible selection
- Optimal parametric payout
- Budget-constrained insurance
- Premium pricing
- Utility comparison
- Sensitivity analysis
- Python implementation

---

### Project B — Pricing a Structured Swap

The second project develops a pricing framework for a structured financial product consisting of:

- Euribor floating leg
- Fixed spread leg
- Equity-linked Asian basket coupon

The valuation is performed under the risk-neutral measure using Monte Carlo simulation.

Main topics include:

- Bootstrap of the discount curve
- Discount factors
- Forward rates
- Geometric Brownian Motion (GBM)
- Correlated asset simulation
- Asian basket option pricing
- Monte Carlo pricing
- Greeks computation
- Delta hedging
- Interest-rate DV01
- Hedging with Interest Rate Swaps

---

## Repository Structure

```text
.
├── Project_A/
│   ├── report.pdf
│   ├── src/
│   └── figures/
│
├── Project_B/
│   ├── report.pdf
│   ├── src/
│   └── figures/
│
├── requirements.txt
└── README.md
```

---

## Mathematical Models

### Project A

- Compound Poisson Process
- Censored Exponential Distribution
- Mean-Variance Utility
- Expected Value Premium Principle

### Project B

- Risk-Neutral Pricing
- Discount Curve Bootstrap
- Geometric Brownian Motion
- Correlated Brownian Motions
- Monte Carlo Simulation
- Black-Scholes benchmark

---

## Technologies

- Python
- NumPy
- SciPy
- Pandas
- Matplotlib

---

## Results

### Insurance Project

- Comparison between classical and parametric insurance
- Optimal deductible and payout computation
- Utility comparison under different loading factors
- Indifference threshold analysis

### Structured Product Project

- Fair upfront valuation
- Monte Carlo pricing
- Equity Delta computation
- Interest-rate DV01
- Hedging strategy construction
- Monte Carlo validation against analytical benchmark

---

## References

The implementation follows the methodologies presented during the **Advanced Mathematical Models in Finance** course together with standard quantitative finance models including:

- Compound Poisson insurance models
- Mean-Variance portfolio theory
- Geometric Brownian Motion
- Black-Scholes framework
- Risk-neutral valuation

---

## Authors

- Hannah Bessler
- Ettore Cirillo
- Lorenzo Mariani
- Davide Mauri
- Tommaso Tron
