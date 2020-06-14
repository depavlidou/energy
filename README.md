# energy
Repo for energy analytics coursework, where a daily forecast for the day-ahead load in the UK was required given information on prior load, temperature forecasts for 3 cities and a 'lockdown_index'. The index was published by University of Oxford and represented the stringency of lockdown measures. As a reference, our model showed that the impact of lockdown was approx 20% reduction in energy consumption.

The 'Energy_SARIMAX' jupyter notebook explores the use of a seasonal ARIMA model and exogenous variables (temperature, an indicator of holiday and the lockdown stringency index).

The 'Energy_Analytics_Forecasting' uses a basic regression model, with similar features included and a 1-period lag.
