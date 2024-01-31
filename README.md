# R codes to reproduce the numerical results in the application described in the article "Wu, S., Beaulac, C. & Cao, J. Neural networks for scalar input and functional output. Stat Comput 33, 118 (2023). https://doi.org/10.1007/s11222-023-10287-3".


1. asfr.RData: the age-specific fertility rate (ASFR) data set.

2. Functions.R: includes the main functions to impletment the proposed methods (NNBB, NNSS, NNBR & NNSR), along with two existing models (FoS and FAM), and perform hyperparameter tuning for all approaches. This file needs to be sourced.

3. RealApplication.R: contains the R codes for analyzing the age-specific fertility rate data set using the proposed models (NNBB, NNSS, NNBR & NNSR) and the existing approaches (FoS and FAM). 
