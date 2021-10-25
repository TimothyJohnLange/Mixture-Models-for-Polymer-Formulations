## Mixture-Models-for-Polymer-Formulations
Mixture Model Regression analysis for Polynomial Formulations

# 1) General hierarchical stepwise regression-AICc-Scheffe-Becker-InvLog-2nd-new.ipynb:
Fit Scheffe or Becker polynomial mixture models using General hierarchical step-wise regression
Requires: experimental.csv and Response.csv

Function:
'model_fit(experimental_file, response_file, response, model_type, inv_log, order)'

Parameters to define:
a) repsonse
b) model type: Scheffe or Becker
c) inv_log: inv, log or None to add inverse or logarithmic boundry terms or neither
d) order: 2 or 3 to define polynomial model order
