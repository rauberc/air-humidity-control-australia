# Relative air humidity control in Sydney, Australia

This is the code used in the second application of the paper [Residual-based CUSUM beta regression control chart for monitoring double-bounded processes
](https://onlinelibrary.wiley.com/doi/abs/10.1002/qre.3140) from Cristine Rauber, Luiz M. A. Lima-Filho, and Fábio M. Bayer.

# Data 

The dataset refers to the relative humidity (RH) in Australia and highlights the relevance of the proposed chart in monitoring double bounded environmental data. The RH is a ratio between continuous numbers, being the ratio of the partial pressure of water to the equilibrium vapor pressure of water, assuming values in (0,1). Due to the genesis of the beta regression model, rates and proportions usually can be well fitted by this model. Additionally, the monitoring of RH is relevant because it exerts influence on temperature, rain, and thermal sensation. This dataset is available in the **rattle** package in R. However, the data has been updated so the results presented here do not reflect the results in the paper.

# Description of the features used in the beta regression model.

RelHumid3pm - Relative humidity (%) at 3pm
Cloud3pm - Fraction of sky obscured by cloud at 3pm
Evaporation - The so-called Class A pan evaporation (mm) in the 24h to 9am
MaxTemp - The maximum temperature in degrees celsius
MinTemp - The minimum temperature in degrees celsius
Pressure3pm - Atmospheric pressure reduced to mean sea level at 3pm
Rainfall - The amount of rainfall recorded for the day in mm
Sunshine - The number of hours of bright sunshine in the day


# How to cite this work

Rauber, C., Lima‐Filho, L. M., & Bayer, F. M. (2022). Residual‐based CUSUM beta regression control chart for monitoring double‐bounded processes. Quality and Reliability Engineering International.


# Contact

Cristine Rauber (rauberoliveira at gmail.com)

# License

[MIT](https://github.com/rauberc/humidity-control/blob/main/LICENSE)
