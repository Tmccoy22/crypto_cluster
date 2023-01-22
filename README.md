# Crypto Cluster Unsupervisor Learning Challenge

This is a Jupyter Notebook that does unsupervised learning using K clusters and PCA predictions. This application looks the proformance of cyrptocurrecnies clusters by their performance in different time periods. We then plottde the results so we can visually show the performance.
---

## Technologies

This project leverages python 3.7 with the following packages:

* [pandas](https://github.com/pandas-dev/pandas) - For the command line interface, help page, and entrypoint.

* [hvplot](https://github.com/holoviz/hvplot) - A high-level plotting API for pandas, dask, xarray, and networkx built on HoloViews

* [metaplot](https://github.com/matplotlib/matplotlib) - For entrypoint and help page.

* [KMeans](https://github.com/topics/k-means-clustering) - To associate your repository with the k-means-clustering

* [PCA]https://github.com/erdogant/pca) - pca: A Python Package for Principal Component Analysis.

* [StandardScaler](https://github.com/topics/standard-scaler) - 

---

## Installation Guide

Before running the application first install the following dependencies.

```
import pandas as pd
import hvplot.pandas
from pathlib import Path
from sklearn.cluster import KMeans
from sklearn.decomposition import PCA
from sklearn.preprocessing import StandardScaler
```


---

## Usage

Acitvate a Jupyter Lab Notebook by having the kernal installed and typing `jupyter lab` in your terminal. 

---

## Examples
```
for i in k:
    model = KMeans(n_clusters=i, random_state=0)
    model.fit(df_market_data_scaled)
    inertia.append(model.inertia_)
    
inertia
```

---

## Contributors

DU Starter Code
Terrence McCoy


---

## License

MIT
