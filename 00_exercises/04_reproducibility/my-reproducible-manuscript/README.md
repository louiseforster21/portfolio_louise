# My Reproducible Manuscript

This repository contains the files, data and script needed to reproduce my research.

The research looks at that the impact of measurement error on linear regression analysis. It is a simulation study originally conducted by Boulesteix et al. (2020). The original paper can be found here: https://bmjopen.bmj.com/content/10/12/e039921#DC1

# Repository structure
In the compodium you fill find different files, namely:
- ## Data: The data folder contains five datasets used in the analyses
  1. DEMO_I.xpt -> Demographic Variables and Sample Weights
  2. BPX_I.xpt -> Blood Pressure
  3. BMX_I.xpt -> Body Measures
  4. GHB_I.xpt -> Glycohemoglobin
  5. TCHOL_I.xpt -> Cholesterol - Total
- ## Docs: The docs contains the following two documents related to the replicaion
  1. Replication Bouleseix simulation.qmd - The Quarto document containing the R code and explenations used to replicate the simulation study.
  2. Replication Boulesteix simulation.html - The rendered HTML version of the Quarto document.
  3. Renv.lock - can be used to obain the package versions used during this analyses
- ## Results: The results file contains the output of the simulation study
  1. Simulation_results_visualisation.pdf - A visualisation of the simulation results, illustrating the infuence of measurement error. 
- ## Scrips: The scripts file contains the original source code used for the simulation study
 
# Additional notes:
During the analyses certain variables were renamed to improve readability. The following provides an overview of the original variable names and their description:
- RIAGENDR - Gender
- RIDAGEYR - Age in years at screening
- BPXSY1 - Systolic: Blood pres (1st rdg) mm Hg
- BMXBMI - Body Mass Index (kg/m**2)
- LBDTCSI - Total Cholesterol (mmol/L)
