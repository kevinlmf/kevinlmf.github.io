---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---


## Quantitative-Trading-System
Modular backtesting and execution framework with **C++ acceleration**.  
Supports plug-and-play strategies, portfolio risk analytics (Sharpe, drawdown), and scalable multi-asset backtests.  
🔗 [GitHub](https://github.com/kevinlmf/Quantitive-Trading-System)

```plaintext
Quantitative-Trading-System/
├── cpp_core/          # C++ engine & bindings (optional, high-performance)
├── data/              # Sample datasets & ETL pipeline
├── env/               # Gym-style trading environments
├── execution_engine/  # Python execution simulator
├── risk_control/      # Risk metrics & portfolio risk limits
├── strategy/          # Momentum, Pairs Trading, Mean-Variance
└── scripts/           # Tests, demos, utilities
```

---

## Portfolio_Optimization_System
Integrates **machine learning alpha factors** with **copula/CVaR risk modeling**.  
Provides a full pipeline from signal generation to stress-tested portfolio allocation and efficient frontier visualization.  
🔗 [GitHub](https://github.com/kevinlmf/Portfolio_Optimization)

```plaintext
Portfolio_Optimization_System/
├── data/                 # Data acquisition and processing
├── strategy/             # Factor research & optimization engine
├── risk_control/         # Risk management modules
├── execution_engine/     # Portfolio execution environment
├── scripts/              # Main entry points
└── results/              # Outputs & analytics
```

---

## HFT_System
Research and backtesting framework for **high-frequency trading signals**.  
Focuses on microstructure-based factor analysis (order flow, liquidity) and testing methods from classical time-series to deep learning (LSTM, Transformer).  
🔗 [GitHub](https://github.com/kevinlmf/HFT_System)

```plaintext
HFT_System/
├── run_complete_pipeline.py     # End-to-end signal pipeline
├── run_strategy_comparison.py   # Unified strategy comparison
├── data/                        # Data download and storage
├── signal_engine/               # Feature engineering and ML signals
├── strategy_methods/            # ML / Traditional / DL / RL implementations
├── evaluation/                  # Backtesting and performance metrics
├── exports/                     # Results (signals, metrics, reports)
└── README.md
```
