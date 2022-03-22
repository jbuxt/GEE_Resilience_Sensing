# GEE_Resilience_Sensing
Google Earth Engine script for Javascript API for calculating resilience trends of MODIS NDVI data. This uses multi-annual averages and a moving average to remove seasonal cycles and trend, before calculating lag-1 autocorrelation (AR(1)) as a proxy for resilience and calculating the Mann-Kendall tau value to indicate the trend in vegetation resilience (see Lenton et al., 2022 for details).

Code author: Joshua Buxton [Uni. Exeter]

Written for: Lenton et al., 2022: "A resilience sensing system for the biosphere", PhilTransB, https://doi.org/10.1098/rstb.2021.0383 - used to generate Figure 2 and Figure 3
