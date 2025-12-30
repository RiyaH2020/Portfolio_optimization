# Portfolio Optimization with Classical and Quantum Methods

This repository implements classical portfolio optimization using the Markowitz mean–variance framework and establishes a strong baseline for future quantum optimization using QUBO and QAOA.

The current focus is on data preparation, convex optimization with modern solvers, and empirical analysis on real market data.

---

## What’s Implemented

- **Markowitz Mean–Variance Portfolio Optimization**
- **Classical optimization using CVXPY with the Clarabel solver**
- **Monte Carlo portfolio simulation**
- **Real market data preprocessing (NIFTY 50)**
- **Sensitivity analysis across different risk preferences**

---

## Work Completed

### 1. Theory & Background
- Studied Modern Portfolio Theory and classical portfolio optimization methods
- Reviewed optimization formulations relevant to quantum computing
- Authored a **3–4 page literature review** on classical and emerging quantum approaches

### 2. Classical Optimization Baseline
- Selected **10 stocks across 3 different sectors**
- Computed optimized portfolios for **three risk-aversion levels**
- Compared:
  - Monte Carlo–simulated portfolios
  - Convex optimization solutions using **Clarabel**
- Analyzed expected return, variance, and asset allocation behavior

### 3. Data Engineering
- Dataset: **NIFTY 50 stock market data**
- Performed data cleansing, consolidation, and yearly return computation
- Built reusable preprocessing pipelines for optimization experiments

### 4. Solver Analysis
- Implemented optimization solvers in Python
- Evaluated:
  - Optimized portfolio weights
  - Expected return and risk
- Re-estimated portfolios under different solver parameters and interpreted asset selection

---

## Tools & Technologies

- Python
- NumPy, Pandas
- **CVXPY (Clarabel solver)**
- SciPy
- Matplotlib
- Jupyter Notebook

---

