---
title: Pyqg parameterization benchmarks
jobtitle: Dataset
datasettype: Benchmark
paper: 'https://onlinelibrary.wiley.com/doi/abs/10.1029/2022MS003258'
website: 'https://m2lines.github.io/MLwithQG/intro.html'
code: 'https://github.com/m2lines/pyqg_parameterization_benchmarks'
---

<!-- Datasets: hosted on globus, access as described [here](https://github.com/m2lines/pyqg_parameterization_benchmarks/blob/master/notebooks/dataset_description.ipynb), e.g.:
```
import xarray as xr
import fsspec
# Datasets are hosted on globus as zarr files
def get_dataset(path, base_url="https://g-402b74.00888.8540.data.globus.org"):
    mapper = fsspec.get_mapper(f"{base_url}/{path}.zarr")
    return xr.open_zarr(mapper, consolidated=True)
``` -->
