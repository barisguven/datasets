# Tidymodels Datasets for Scikit-learn

This repository contains the CSV versions of `ames` and `stackoverflow` datasets from the **modeldata** package in **tidymodels**, an R meta-package for machine learning and statistical analysis. Both datasets could be used as additional example datasets for the Python package **scikit-learn**.

Use the following Python code to create a pandas DataFrame from `ames`:

```python
import pandas as pd

ames = pd.read_html()
```