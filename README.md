# Tidymodels Datasets for Scikit-learn

This repository contains the CSV versions of the `ames` and `stackoverflow` datasets from the **modeldata** package in **tidymodels**, an R meta-package for machine learning and statistical analysis. Both datasets could be used as additional example datasets for the Python package **scikit-learn**.

Use the following Python code to create a pandas DataFrame for the `ames` dataset:

```python
import pandas as pd

ames = pd.read_csv("https://raw.githubusercontent.com/barisguven/datasets/main/data/ames_tm.csv")
```