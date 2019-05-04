# Self generating data classifier

The two-dimensional data X ∈ R2 in each class is generated from a mixture of 10 different bivariate Gaussian distributions with uncorrelated
components and different means.

The code generates a training sample of size 200 and a test sample of size 10,000, and calculates the training and test errors (the averaged 0/1 error)
for the following four procedures:
- Linear regression with cut-off value 0.5
- quadratic regression with cut-off value 0.5
- kNN classification with k chosen by 10-fold cross-validation
- the Bayes rule
