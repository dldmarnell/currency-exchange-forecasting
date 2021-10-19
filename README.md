# A Yen for the Future

The included notebooks applies time series analysis and modeling in order to predict future movements in the value of the Japanese yen versus the U.S. dollar. The time_series_analysis notebook loads historical Dollar-Yen exchange rate futures data and uses the Hodrick-Prescott Filter as well as ARMA, ARIMA and GARCH models to determine whether there is any predictable behavior. The regression_analysis notebook builds a Scikit-Learn linear regression model to predict Yen future returns with lagged Yen future returns and categorical calendar seasonal effects.

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

- An ARMA model is used to predict Yen returns over a five day period
![returns_forecast](Resources/Images/arma_returns_forecast.png)

- Based on the p-values of the lags, an ARMA is not a good fit for this data because all values are greater than 0.05, meaning there is no statistically relevant data present
![arma_summary](Resources/Images/arma_summary.png)

- An ARIMA model is used to predict the settle price of Yen over a five day period
![price_forecast](Resources/Images/arima_price_forecast.png)

- The model predicts that Yen will rise by 4 over the next 5 days. However, since all p-values are greater than 0.05 we know that no statistically relevant data is present and the model is not a good fit
![arima_summary](Resouces/Images/arima_summary.png)

- 



---

## Contributors

Drew Disbrow Marnell: dldmarnell@gmail.com

---

## License

MIT License
Copyright (c) 2021 Drew Disbrow Marnell
