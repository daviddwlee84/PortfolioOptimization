# Portfolio Management and Optimization

1. Factor Investing => Build Portfolio (Management)
2. Portfolio Optimization (Risk Management...)

## Getting Started

```bash
# Use conda
# conda create --prefix .venv python=3.9
# conda activate ./.venv

# Use venv (more lightweight)
# (Using Python 3.12)
python -m venv .venv
source .venv/bin/activate

pip install -r requirements.txt
jupyter notebook
```

```bash
pip install -i https://pypi.tuna.tsinghua.edu.cn/simple -U "vectorbtpro[base] @ git+ssh://git@github.com/polakowo/vectorbt.pro.git" 
# During installation: fatal error: 'H5public.h' file not found
brew install hdf5
```

## Resources

### Library

Portfolio Performance Statistics Summary and Backtesting

- [ranaroussi/quantstats: Portfolio analytics for quants, written in Python](https://github.com/ranaroussi/quantstats) - Better for daily or lower frequency portfolio returns summary (kind of buggy)
- [polakowo/vectorbt: Find your trading edge, using the fastest engine for backtesting, algorithmic trading, and research.](https://github.com/polakowo/vectorbt) - Better to analysis intraday or multiple instruments trading details
  - [qs_adapter - vectorbt](https://vectorbt.dev/api/returns/qs_adapter/) - using VectorBT with QuantStats
- [VectorBT PRO](https://vectorbt.pro/) ([polakowo/vectorbt.pro](https://github.com/polakowo/vectorbt.pro)) - Introduce portfolio related feature then open-source VectorBT
  - [Portfolio - VectorBT PRO](https://vectorbt.pro/features/portfolio/)
- [stefan-jansen/pyfolio-reloaded: Portfolio and risk analytics in Python](https://github.com/stefan-jansen/pyfolio-reloaded)
  - [pyfolio — pyfolio 0.9.3+28.g3dcf744 documentation](https://pyfolio.ml4trading.io/)
    - [Intro — pyfolio 0.9.3+28.g3dcf744 documentation](https://pyfolio.ml4trading.io/notebooks/single_stock_example.html#Download-daily-stock-prices-using-yfinance)
  - (deprecated) [quantopian/pyfolio: Portfolio and risk analytics in Python](https://github.com/quantopian/pyfolio)
    - [pyfolio](https://quantopian.github.io/pyfolio/)
      - [Single stock - pyfolio](https://quantopian.github.io/pyfolio/notebooks/single_stock_example/)

### Example

- [[CVXPY] Portfolio Optimization Example](https://www.kaggle.com/code/marketneutral/cvxpy-portfolio-optimization-example)
- [cvx_short_course/book/docs/applications/notebooks/portfolio_optimization.ipynb at master · cvxgrp/cvx_short_course](https://github.com/cvxgrp/cvx_short_course/blob/master/book/docs/applications/notebooks/portfolio_optimization.ipynb)
  - [Google Colab](https://colab.research.google.com/github/cvxgrp/cvx_short_course/blob/master/book/docs/applications/notebooks/portfolio_optimization.ipynb)
  - [cvxgrp/cvx_short_course: Materials for a short course on convex optimization.](https://github.com/cvxgrp/cvx_short_course)
- [🤑 Data Science for Financial Markets 📈💰](https://www.kaggle.com/code/lusfernandotorres/data-science-for-financial-markets#optimizing-portfolio)
- [AnnaSkarpalezou/Portfolio-Optimization-using-Machine-Learning: This repository is the result of our work for the course CSCI-SHU 360 Machine Learning](https://github.com/AnnaSkarpalezou/Portfolio-Optimization-using-Machine-Learning) (a super naive project, the Sharpe ratio is super low)

### Paper and Thesis

- [Multi-Period Trading via Convex Optimization](https://stanford.edu/~boyd/papers/pdf/cvx_portfolio.pdf)
- [Portfolio Management And Optimal Execution Via Convex Optimization](https://stacks.stanford.edu/file/druid:wm743bj5020/thesis-augmented.pdf)
- [Markowitz Mean-Variance Portfolio Theory](https://sites.math.washington.edu/~burke/crs/408/fin-proj/mark1.pdf)

### Article

- [组合优化 - 阅微堂](https://zhiqiang.org/tag/portfolio-optimization.html)
- [浅谈指数增强-腾讯云开发者社区-腾讯云](https://cloud.tencent.com/developer/article/1424201)
- [组合优化（一）：换手率和alpha模型-腾讯云开发者社区-腾讯云](https://cloud.tencent.com/developer/article/2242060)
- [组合优化(二):换手约束下的最优模型-腾讯云开发者社区-腾讯云](https://cloud.tencent.com/developer/article/2242059)

### Book

- [Quantitative Equity Portfolio Management, 2nd Edition | Ludwig B. Chincarini](https://ludwigbc.com/books/qepm-2/)
- [Your Complete Guide to Factor-based Investing: The Way Smart Money Invests Today - Andrew L. Berkin, Larry E. Swedroe - Google Books](https://books.google.co.jp/books/about/Your_Complete_Guide_to_Factor_based_Inve.html?id=iSNBvgAACAAJ&redir_esc=y)
- [Machine Learning for Factor Investing](https://www.mlfactor.com/)
  - [viniesposito/py-mlfactor: Rewriting the code in "Machine Learning for Factor Investing" in Python](https://github.com/viniesposito/py-mlfactor)
  - [shokru/mlfactor.github.io: Website dedicated to a book on machine learning for factor investing](https://github.com/shokru/mlfactor.github.io?tab=readme-ov-file)
    - [Dataset](https://github.com/shokru/mlfactor.github.io/tree/master/material)
  - [Chapter 18 Python notebooks | Machine Learning for Factor Investing](https://www.mlfactor.com/python.html)

### Data

- [Market Data Home](https://finra-markets.morningstar.com/MarketData/Default.jsp?sdkVersion=2.62.9)
  - 10-years U.S. Treasury Benchmarks => Risk Free Return $R_f$
- [Target Corporation (TGT) Stock Price, News, Quote & History - Yahoo Finance](https://finance.yahoo.com/quote/TGT/?p=TGT&.tsrc=fin-srch)
  - 5-Year Monthly => Beta

### Video

- [Deep portfolio: using neural networks for portfolio construction - Anant Gupta - YouTube](https://www.youtube.com/watch?v=7LOb9kk6U_M) - Basic knowledge of what Portfolio is
- [Python - Finance - Portfolio Optimization - YouTube](https://www.youtube.com/playlist?list=PLcFcktZ0wnNnqefRpFMS1k9_VlhVw7bzc)
