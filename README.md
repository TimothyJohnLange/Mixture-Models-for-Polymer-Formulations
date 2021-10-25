# Mixture-Models-for-Polymer-Formulations
Mixture Model Regression analysis for Polynomial Formulations

## 1) General hierarchical stepwise regression-AICc-Scheffe-Becker-InvLog-2nd-new.ipynb:

Fit Scheffe or Becker polynomial mixture models using General hierarchical step-wise regression
Requires: experimental.csv and Response.csv

Function:

'model_fit(experimental_file, response_file, response, model_type, inv_log, order)'

Parameters to define:

a) repsonse

b) model type: Scheffe or Becker

c) inv_log: inv, log or None to add inverse or logarithmic boundry terms or neither

d) order: 2 or 3 to define polynomial model order

## 2) Hierarchical backward regression.ipynb:

Fit Scheffe or Becker polynomial mixture models using Hierarchical backward regression

Requires: experimental.csv and Response.csv

Function:

'model_fit(experimental_file, response_file, response, model_type, order, inv_log)'

Parameters to define:

a) repsonse

b) model type: Scheffe or Becker

c) inv_log: inv, log or None to add inverse or logarithmic boundry terms or neither

d) order: 2 or 3 to define polynomial model order

## 3) BrownPiepel stepwise function - (no linear removal)-2nd.ipynb:

Fit Scheffe or Becker polynomial mixture models using Quadratic step-wise regression

Requires: experimental.csv and Response.csv

Function:

'model_fit(experimental_file, response_file, response, model_type, inv_log)'

Parameters to define:

a) repsonse

b) model type: Scheffe or Becker

c) inv_log: inv, log or None to add inverse or logarithmic boundry terms or neither

## 4) Branched step-wise regression with conditioning-2nd Scheffe.ipynb:
Fit Scheffe polynomial mixture models using Conditioned hierarchical step-wise regression
Requires: experimental.csv and Response.csv

Function:
'model_fit(experimental_file, response_file, response, inv_log, cond_limit, VIF_limit)'

Parameters to define:
a) repsonse
b) inv_log: inv, log or None to add inverse or logarithmic boundry terms or neither
c) cond_limit: conditioning number limit
d) VIF_limit: VIF_max limit


## 5) Fit_TotalSubset_AIC_BIC.ipynb:
Fit Scheffe polynomial mixture models using best subset regression and analytical selection criteria (AICc, BIC, AIC)
Requires: experimental.csv, Response.csv and Total_model_subset.csv (not included in repo due to size)

## 6) Fit_TotalSubset_Kfold.ipynb:
Fit Scheffe polynomial mixture models using best subset regression and K-fold selection criteria
Requires: experimental.csv, Response.csv and Total_model_subset.csv (not included in repo due to size)

## 7) Data analysis:
a) CompareCriteria_FINAL.ipynb
b) Kfold_Tuning_BiasVariance_FINAL.ipynb
c) ModelComplexityGraph_final.ipynb
d) Conditioning results_best subset regression_Final.ipynb

