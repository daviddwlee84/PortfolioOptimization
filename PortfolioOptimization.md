# Portfolio Optimization

## Modern Portfolio Theory (MPT)

- [Modern Portfolio Theory (MPT) - Wikipedia](https://en.wikipedia.org/wiki/Modern_portfolio_theory)

### Markowitz Mean-Variance Optimization Model

- [Markowitz model - Wikipedia](https://en.wikipedia.org/wiki/Markowitz_model)

The HM (Harry Markowitz) Model is also called mean-variance model due to the fact that it is based on expected returns (mean) and the standard deviation (variance) of the various portfolios. It is foundational to Modern portfolio theory.

> - Portfolio return is the proportion-weighted combination of the constituent assets' returns
> - Portfolio return volatility σ is a function of the correlations ρij of the component assets, for all asset pairs (i, j). The volatility gives insight into the risk which is associated with the investment. The higher the volatility, the higher the risk.

1. Portfolio Expected Return
2. Portfolio Variance

- [Lesson 5:Mean-Variance Optimization of Portfolios](https://www.kaggle.com/code/vijipai/lesson-5-mean-variance-optimization-of-portfolios)
  - [Dr G A Vijayalakshmi Pai | Novice | Kaggle](https://www.kaggle.com/vijipai/code)

### Efficient Frontier (Portfolio Frontier)

- [Efficient frontier - Wikipedia](https://en.wikipedia.org/wiki/Efficient_frontier)

![Markowitz Frontier](https://upload.wikimedia.org/wikipedia/commons/e/e1/Markowitz_frontier.jpg)

![Parametric Plot](https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/CAPM2.png/350px-CAPM2.png)

## Asset Allocation Model

### Black-Litterman Allocation Model

> although the covariances of a few assets can be adequately estimated, it is difficult to come up with reasonable estimates of expected returns

- [Black–Litterman model - Wikipedia](https://en.wikipedia.org/wiki/Black%E2%80%93Litterman_model)
- [Black-Litterman Model: Definition, Basics, and Example](https://www.investopedia.com/terms/b/black-litterman_model.asp)

## Resource

### Library

Optimization

- [cvxgrp/cvxportfolio: Portfolio optimization and back-testing.](https://github.com/cvxgrp/cvxportfolio)
  - [Cvxportfolio 1.3.2 documentation](https://www.cvxportfolio.com/en/stable/)
- [cvxpy/cvxpy: A Python-embedded modeling language for convex optimization problems.](https://github.com/cvxpy/cvxpy)
  - [Examples — CVXPY 1.5 documentation](https://www.cvxpy.org/examples/)
- [robertmartin8/PyPortfolioOpt: Financial portfolio optimisation in python, including classical efficient frontier, Black-Litterman, Hierarchical Risk Parity](https://github.com/robertmartin8/PyPortfolioOpt) (`pypfopt`)
  - [Installation — PyPortfolioOpt 1.5.4 documentation](https://pyportfolioopt.readthedocs.io/en/latest/)
  - [PyPortfolioOpt — PyPortfolioOpt 中文文档 1.5.5 文档](https://www.wuzao.com/document/pyportfolioopt/index.html)
  - [Portfolio Optimization: The Markowitz Mean-Variance Model | by Luís Fernando Torres | LatinXinAI | Medium](https://medium.com/latinxinai/portfolio-optimization-the-markowitz-mean-variance-model-c07a80056b8a)
- [The Leader in Decision Intelligence Technology - Gurobi Optimization](https://www.gurobi.com/)
  - [Portfolio Optimization with Gurobi - Gurobi Optimization](https://www.gurobi.com/jupyter_models/portfolio-selection-optimization/)
  - [austingriffith94/simple_portfolio_optimization: A simple portfolio optimization using the Gurobi optimization package in Python.](https://github.com/austingriffith94/simple_portfolio_optimization)
  - [portfolio.py - Gurobi Optimization](https://www.gurobi.com/documentation/current/examples/portfolio_py.html)
  - [Portfolio Optimization with Gurobi - Gurobi Optimization](https://www.gurobi.com/jupyter_models/portfolio-selection-optimization/)
- [Mosek ApS](https://www.mosek.com/)
  - [MOSEK/PortfolioOptimization: Material accompanying the MOSEK Portfolio Optimization Cookbook](https://github.com/MOSEK/PortfolioOptimization)
  - [MOSEK Portfolio Optimization Cookbook — MOSEK Portfolio Optimization Cookbook 1.6.0](https://docs.mosek.com/portfolio-cookbook/index.html)
- [minimize — SciPy v1.14.1 Manual](https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.minimize.html)
- [dcajasn/Riskfolio-Lib: Portfolio Optimization and Quantitative Strategic Asset Allocation in Python](https://github.com/dcajasn/Riskfolio-Lib)
  - [Riskfolio-Lib 6.3](https://riskfolio-lib.readthedocs.io/en/latest/)
  - [Riskfolio-Lib — Riskfolio-Lib 中文文档 4.4.2 文档](https://www.wuzao.com/document/riskfolio-lib/)

Optimize Hyperparameter

- [optuna/optuna: A hyperparameter optimization framework](https://github.com/optuna/optuna)
  - [Optuna - A hyperparameter optimization framework](https://optuna.org/)
  - [Optuna: A hyperparameter optimization framework — Optuna 4.1.0 documentation](https://optuna.readthedocs.io/en/stable/)
- [hyperopt/hyperopt: Distributed Asynchronous Hyperparameter Optimization in Python](https://github.com/hyperopt/hyperopt)
  - [Hyperopt Documentation](https://hyperopt.github.io/hyperopt/)
- [Ray Tune: Hyperparameter Tuning — Ray 2.40.0](https://docs.ray.io/en/latest/tune/index.html)
- [GridSearchCV — scikit-learn 1.6.1 documentation](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html)
- [brute — SciPy v1.15.0 Manual](https://docs.scipy.org/doc/scipy-1.15.0/reference/generated/scipy.optimize.brute.html)

Deep Learning

- [jankrepl/deepdow: Portfolio optimization with deep learning.](https://github.com/jankrepl/deepdow)
- [[2005.13665] Deep Learning for Portfolio Optimization](https://arxiv.org/abs/2005.13665)
- [qlib/examples/tutorial/detailed_workflow.ipynb at main · microsoft/qlib](https://github.com/microsoft/qlib/blob/main/examples/tutorial/detailed_workflow.ipynb)
