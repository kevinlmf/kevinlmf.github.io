---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

# Quant Projects

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

Together, these three projects form a comprehensive toolkit for **quantitative finance**, covering the spectrum from **long-term portfolio optimization** to **short-term high-frequency trading**, integrating both **financial engineering** and **machine learning** methods.

---

# MLE Projects

## JAX_Inventory_Optimizer
High-performance **inventory optimization system** using JAX.  
Compares traditional methods with modern **ML demand forecasting** and **RL policy learning** (DQN, PPO, SAC).  
🔗 [GitHub](https://github.com/kevinlmf/JAX_Inventory_Optimizer)

```plaintext
JAX_Inventory_Optimizer/
├── src/                # Core implementations (traditional, ML, RL)
├── experiments/        # Comparative experiments
├── notebooks/          # Jupyter analysis
├── configs/            # Config files (YAML)
├── results/            # Experimental outputs
├── examples/           # Usage examples
└── tests/              # Unit tests
```

---

## Sports_Injury_Risk
End-to-end **sports injury risk prediction system** with traditional ML, deep learning, and survival analysis.  

Includes **feature engineering** (rolling windows, workload ratios), **multi-modal data** (demographics, performance, injury history), and a **real-time API** for predictions and interpretability.
 
🔗 [GitHub](https://github.com/kevinlmf/Sports-Injury-prediction)

```plaintext
Sports_Injury_Risk/
├── src/
│   ├── data/                   # Data processing and feature engineering
│   │   ├── loader.py           # Data loading utilities
│   │   ├── features.py         # Feature engineering pipeline
│   │   ├── validate.py         # Data validation
│   │   └── contracts.py        # Data schemas
│   ├── methods/                # Model implementations
│   │   ├── traditional/        # Random Forest, Logistic Regression, XGBoost
│   │   ├── dl_seq/             # LSTM, GRU, Transformer
│   │   ├── survival/           # Cox, DeepSurv, DeepHit
│   │   └── ensemble/           # Model combination strategies
│   ├── core/                   # Core training and evaluation
│   │   ├── trainer.py          # Model training orchestration
│   │   ├── metrics.py          # Evaluation metrics
│   │   ├── interpret.py        # Model interpretability
│   │   └── calibration.py      # Probability calibration
│   └── api/                    # FastAPI service
│       └── main.py             # API endpoints and documentation
├── experiments/                # Experimental scripts
│   ├── train_model.py          # Model training pipeline
│   ├── evaluate_model.py       # Model evaluation
│   └── compare_models.py       # Model comparison
├── examples/                   # Usage examples
│   └── quick_start.py          # Getting started demo
├── configs/                    # Configuration files
│   ├── train_config.yaml       # Training configuration
│   ├── eval_config.yaml        # Evaluation configuration
│   └── api_config.yaml         # API configuration
├── data/                       # Data storage
├── models/                     # Trained model artifacts
├── results/                    # Experimental results
└── notebooks/                  # Analysis notebooks
```

---
Together, these two projects emphasize complementary aspects of **machine learning engineering** 

**JAX_Inventory_Optimizer** highlights algorithmic design and system implementation, while **Sports_Injury_Risk** focuses on data-driven analysis and predictive modeling.  

---
Overall, these projects are still under **active development**, aiming to integrate robust **algorithmic implementations** with **data-driven analysis**, and are expected to generate increasingly significant outcomes as the systems **mature**.

---
