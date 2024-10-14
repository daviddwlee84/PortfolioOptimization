# Dataset

## Machine Learning for Factor Investing

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

---

## Resources

- [ofajardo/pyreadr: Python package to read and write R RData and Rds files into/from pandas dataframes. No R or other external dependencies required.](https://github.com/ofajardo/pyreadr)
