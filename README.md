# Covid-19 cases in Mexico: A Time Series Analysis
A time series analysis of the Covid-19 cases in Mexico at a national and state level. We used autoregressive models, such as AR, ARIMA and Random Forest regressor to predict future cases and analyze how the pandemic impacted different states throughout the 3 case waves. The data was obtained from the National Council of Science and Technology (Conacyt), which is retrieve from the Health Ministry directly. url: https://datos.covid-19.conacyt.mx/#DownZCSV

The Python programming language was used to trained and test the models using the statsmodels and sklearn libraries. The ARIMA models for each time series was optimized to find the least root mean squared error. It was found that the ARIMA model, in general, outperforms the Random Forest regressor using this metric.

## Treating the data
The covid-19 cases data that is retrieve by the Mexican authorities shows a periodic behaviour with peaks
