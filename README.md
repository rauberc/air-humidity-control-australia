# Humidity control in Australia

This is the code used in the second application of the paper [Residual-based CUSUM beta regression control chart for monitoring double-bounded processes
](https://onlinelibrary.wiley.com/doi/abs/10.1002/qre.3140) from Cristine Rauber, Luiz M. A. Lima-Filho, and Fábio M. Bayer.

# Data 

The dataset refers to the relative humidity (RH) in Australia and highlights the relevance of the proposed chart in monitoring double bounded environmental data. The RH is a ratio between continuous numbers, being the ratio of the partial pressure of water to the equilibrium vapor pressure of water, assuming values in (0,1). Due to the genesis of the beta regression model, rates and proportions usually can be well fitted by this model. Additionally, the monitoring of RH is relevant because it exerts influence on temperature, rain, and thermal sensation. This dataset is available in the **rattle** package in R from October 2010 to June 2017 for the Sydney Station in Australia.

# How to cite this work

Rauber, C., Lima‐Filho, L. M., & Bayer, F. M. (2022). Residual‐based CUSUM beta regression control chart for monitoring double‐bounded processes. Quality and Reliability Engineering International.


# Contact

Cristine Rauber (rauberoliveira at gmail.com)

# License

[MIT](https://github.com/rauberc/humidity-control/blob/main/LICENSE)
