1. load the training and testing data, then split the training data
to mod-training and cross-validation data.
2. clean the data by removing the nearZeroVariance variables,
and variables with too many NAs.
3. use decision tree/random forest etc. to model the mod-training data;
then evaluate the model accuracy on cross-validation data.


