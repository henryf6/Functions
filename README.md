# Cross Validation Functions

This provides functions in R that implement a few different cross validation methods.  The first is a random cross validation that randomly assigns data (rows) to each fold. The second function is a block cross validation where a factor column is used to assign folds.  The last function is a cross validation method that structure folds based on ordered spatial autocorrelation.

The functions currently work for linear models (lm), penalized regression functions (pfr(), library(refund)), and partial least squares regression (plsr(), library(pls)).  Other linear models types can easily be added.
