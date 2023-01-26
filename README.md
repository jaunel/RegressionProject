# RegressionProject

We have used boston housing datset for our problem.
# Data Preprocessing
  check for null values
  check for duplicated entries
  check for correlation among features--if two independent features have strong     positive corelation then we may drop one of them for our problem
    if we have corelation close to zero between independent and dependent           feature then we may drop that dependent feature 
# Standardize the data
  internally our algorithm uses gradient descent which will aim to come near to   global minima so we convert all data in same scale
