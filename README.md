# Machine Learning Algo
This is a jupyter notebook application that observes historical data and patterns that enables an algorithm to machine trade effciently. We give the algorith parameters to create buy and sell signals utilizing the moving averages. There is a variance in moving averages that can be used, as well as the algorithm training duration. 
---

## SVC Model Predictions

![first_plot](https://user-images.githubusercontent.com/117557983/232349950-359bb8d0-2cb3-4413-bcca-4c068c1847f2.png)

---

## AdaBoost Model

![second_plot](https://user-images.githubusercontent.com/117557983/232349963-232709c7-5cf9-41d3-8ef2-b073e54dc6ab.png)


---

## Technologies & Libraries

This project utilizes python 3.7 with the following:

* [Pandas](https://github.com/pandas-dev/pandas) - An Open Source Machine Learning Framework for everyone.

* [Numpy](https://github.com/numpy/numpy) - The fundamental package for scientific computing with Python.

* [Metaplot](https://github.com/matplotlib/matplotlib) - For entrypoint and help page.

* [Imblean.metrics](http://glemaitre.github.io/imbalanced-learn/generated/imblearn.metrics.classification_report_imbalanced.html) - Build a classification report based on metrics used with imbalanced dataset.

* [Sklean.metrics](https://github.com/scikit-learn/scikit-learn) - Simple and efficient tools for predictive data analysis  
    OncHotEncoder, StandardScaler, train_test_split.

---

## Pre Installation Guide

Prior to running this application, please first install the following dependencies:

```
import pandas as pd
import numpy as np
from pathlib import Path
import hvplot.pandas
import matplotlib.pyplot as plt
from sklearn import svm
from sklearn.preprocessing import StandardScaler
from pandas.tseries.offsets import DateOffset
from sklearn.metrics import classification_report

```

---

## Contributors

DU Starter Code

Ben Lindauer

---

## License

MIT
