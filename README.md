# A Yen for the Future

The included notebooks test applies time series analysis and modeling in order to predict future movements in the value of the Japanese yen versus the U.S. dollar. The time_series_analysis notebook loads historical Dollar-Yen exchange rate futures data and uses the Hodrick-Prescott Filter as well as ARMA, ARIMA and GARCH models to determine whether there is any predictable behavior. The regression_analysis notebook builds a Scikit-Learn linear regression model to predict Yen future returns with lagged Yen future returns and categorical calendar seasonal effects.

---

## Technologies

Language: Python3, Pandas 

Imports: pandas, numpy, pathlib, matplotlib, statsmodels.api, statsmodels.tsa.arima_model, arch, sklearn.linear_model, sklearn.metrics 

External Resources: yen.csv

Developed with JupyterLab

---

## Installation

JupyterLab - [Install JupyterLab](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html)

---

## Examples

As we can see here the y value classes are very imbalanced:
![y_class_imbalanced](Resources/Images/balanced_classes.png)

Here is an example of a model, in this case the ClusterCentroid algorithm, balancing the classes uses Undersampling

---

## Contributors

Drew Disbrow Marnell: dldmarnell@gmail.com

---

## License

MIT License
Copyright (c) 2021 Drew Disbrow Marnell