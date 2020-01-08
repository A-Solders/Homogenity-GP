# Homogenity-GP
Exploring ways to fit the homogeneity data using GP

This repository contains Python scripts to fit the homogeneity data from IGISOL 2019. Files included are:

Kernel_Density.ipynb - No really a gaussian process. Uses kernel density to estimate the count rates. No uncertainty estimates available. Boots trapping?

Gauss_proc_GPy.ipynb - fits 1D and 2D data using the GPy library assuming gaussian distributed uncertainties.

Gauss_proc_GPy-Poisson.ipynb - fits 1D and 2D data using the GPy library assuming poisson distributed uncertainties.

Gauss_proc_skilearn.ipynb - To be added
