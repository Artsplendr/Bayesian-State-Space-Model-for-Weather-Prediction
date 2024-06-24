# Bayesian-State-Space-Model-for-Weather-Prediction

#### According to [MathWorks](https://www.mathworks.com/help/econ/bayesian-state-space-model.html#): "A Bayesian state-space model treats the state-space model parameters as random variables, rather than fixed but unknown quantities, with joint prior distribution. This treatment leads to a more flexible model and intuitive inferences."

##### In this project, the Global Historical Climatology Network (GHCN) daily dataset, specifically focusing on temperature data, was used to experiment with Bayesian state-space model for Weather Forecast.  

##### The GHCN dataset is maintained by the National Oceanic and Atmospheric Administration (NOAA) and contains daily climate records from thousands of weather stations worldwide.

* Data Source: NOAA GHCN daily dataset, available at [this link.](https://www1.ncdc.noaa.gov/pub/data/ghcn/daily/by_station/USW00094728.csv.gz)

* Station: For this example, the data used is from the New York, Central Park station (ID: USW00094728).

* Processing: Filtered to include only maximum daily temperatures (TMAX) resampled to monthly averages for analysis.
