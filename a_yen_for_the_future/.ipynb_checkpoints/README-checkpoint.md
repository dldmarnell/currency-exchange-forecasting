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

ARIMA summary output:
![arima_summary_output](Resources/Images/arima_summary.png)

ARIMA forecast plot:
![arima_forecast_plot](Resources/Images/arima_forecast.png)

Predicted Train/Test Split values vs true values plot:
![prediction_vs_true_value_plot](Resources/Images/prediction_vs_true_value_plot.png)




---

## Contributors

Drew Disbrow Marnell: dldmarnell@gmail.com

---

## License

MIT License
Copyright (c) 2021 Drew Disbrow Marnell