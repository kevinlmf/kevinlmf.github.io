---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

## Quantitative-Trading-System
A modular backtesting and execution framework with **C++ acceleration**.  
- Built a high-performance execution engine using C++ and PyBind11, enabling latency-efficient order handling.  
- Designed extensible strategy modules (trend-following, mean-reversion, rule-based) with plug-and-play architecture.  
- Implemented robust **risk analytics** (Sharpe, Sortino, drawdown, volatility) to evaluate portfolio performance.  
- Scales seamlessly from single-asset to multi-asset backtests.  
🔗 [GitHub](https://github.com/kevinlmf/Quantitive-Trading-System)

---

## Portfolio_Optimization_System
A system that integrates **machine learning alpha discovery** with **copula/CVaR-based beta risk modeling**.  
- Developed ML-driven alpha factors using Lasso, Ridge, and tree-based models for signal generation.  
- Applied **copula models** to capture cross-asset dependence structures, improving stress-test robustness.  
- Integrated **CVaR (Conditional Value-at-Risk)** optimization to manage tail risks in portfolio allocation.  
- Provides full pipeline from signal generation → risk modeling → efficient frontier visualization.  
🔗 [GitHub](https://github.com/kevinlmf/Portfolio_Optimization)

---

## HFT_System
An end-to-end **high-frequency trading signal research and backtesting system**.  
- Built a real-time feature engineering pipeline for **tick-level order book data**.  
- Implemented microstructure-based models (Hasbrouck, Kyle’s Lambda) and deep learning models (LSTM, Transformer) for short-term prediction.  
- Designed modules for **signal evaluation** (information coefficient, information ratio, half-life, stability).  
- Provides **backtesting and simulation** environment to test execution strategies and assess market impact.  
🔗 [GitHub](https://github.com/kevinlmf/HFT_System)
