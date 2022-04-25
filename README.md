# GCM
R/JAGS implementation of the cross-domain latent growth curve modeling from "Association between body fat and body mass index from incomplete longitudinal proportion data: Findings from the Fels study" by Tong, Kim, Bandyopadhyay and Sun (2022+). 

Written by Seohyun Kim and edited by Dipankar Bandyopadhyay (Last edited: 04/25/2022)


The code provided implements model-fitting under both the MAR & MNAR scenarios using simulated data. Real data is not provided due to proptietary reasons.

Description: 

1. Folder "Data": includes simulated datasets, under both MAR and MNAR scenarios
2. Folder "JAGS": includes JAGS scripts.
   a. jags_cd_ln_MAR.txt: JAGS script for Ind-CGCM.
   b. jags_cd_ln_MNAR.txt: JAGS script for Ind-CGCM-Selection.
3. Code "estimation_mis.R": R code for running the JAGS scripts.
