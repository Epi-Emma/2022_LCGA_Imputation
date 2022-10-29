# 2022_LCGA_Imputation
Downloadable code to extend the use of Latent Class Growth Analysis (LCGA) models for imputation. 

The R code in this repository was written to read in the LCGA model output files produced by [Mplus software](https://www.statmodel.com/) using the existing [MplusAutomation](https://github.com/michaelhallquist/MplusAutomation) R package. 

--------------
**The files:** 

- *LCGA_Imputation_Process.R* contains code necessary to read in the Mplus LCGA model results and use the resulting estimates to multiply impute the outcome of interest, creating a nested dataset with all imputed datasets. 

- *Oridnal_LCGA_7c_Linear.INP* contains the Mplus code used to conduct the LCGA analysis. The code for the 7 class linear model is included here as it was found ot be the best fitting model for the data. 

--------------
