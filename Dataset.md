# Dataset

## Machine Learning for Factor Investing

> Time Range: November 1998 ~ March 2019
> Feature: 93 characteristics
> Attributes:
> - Valuation
>   - earning yields
>   - accounting ratios
> - Profitability and Quality
>   - return on equity
> - Momentum and Technical Analysis
>   - past returns
>   - relative strength index (RSI)
> - Risk
>   - volatilities
> - Estimates
>   - earnings-per-share
> - Volume
> - Liquidity
>   - share turnover
> Label: total returns - incorporate potential dividend payments over the considered period
> - 1-month ~ 12-month future/forward returns of the stocks

- [mlfactor.github.io/material at master · shokru/mlfactor.github.io](https://github.com/shokru/mlfactor.github.io/tree/master/material)

```bash
wget https://github.com/shokru/mlfactor.github.io/raw/refs/heads/master/material/data_ml.RData
```

```python
import pyreadr
raw_data = pyreadr.read_r("data_ml.RData")
df = raw_data["data_ml"]
df.to_csv("data_ml.csv")
```

[py-mlfactor/py_mlfactor.ipynb at main · viniesposito/py-mlfactor](https://github.com/viniesposito/py-mlfactor/blob/main/py_mlfactor.ipynb)

## Fama-French Data Library

> The most mainstream anomalies

Data Source

- [Kenneth R. French - Data Library](https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html)
  - [Description of Fama/French 5 Factors (2x3)](https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/Data_Library/f-f_5_factors_2x3.html)
    - [csv](https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/ftp/F-F_Research_Data_5_Factors_2x3_CSV.zip)
- [Fama-French Data (Ken French’s Data Library) — pandas-datareader 0.10.0 documentation](https://pandas-datareader.readthedocs.io/en/latest/readers/famafrench.html) ([another link](https://pydata.github.io/pandas-datareader/devel/readers/famafrench.html))
  - [Rolling Regression - statsmodels 0.14.4](https://www.statsmodels.org/stable/examples/notebooks/generated/rolling_ls.html) (example)

Paper

- [A five-factor asset pricing model - ScienceDirect](https://www.sciencedirect.com/science/article/abs/pii/S0304405X14002323)
- [Production of U.S. Rm-Rf, SMB, and HML in the Fama-French Data Library by Eugene F. Fama, Kenneth R. French :: SSRN](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4629613)

Article

- [Fama French Five Factors](https://www.quantconnect.com/research/15262/fama-french-five-factors/p1)

## AQR Data Sets

- [Data Sets](https://www.aqr.com/Insights/Datasets)

## AlternativeData

- [Database - AlternativeData](https://alternativedata.org/data-providers/)

---

## Resources

- [ofajardo/pyreadr: Python package to read and write R RData and Rds files into/from pandas dataframes. No R or other external dependencies required.](https://github.com/ofajardo/pyreadr)

## Financial Data Providers

- Bloomberg
- Thomson-Reuters
- Datastream
- CRSP
- Morningstar
- Capital IQ
- Ravenpack
