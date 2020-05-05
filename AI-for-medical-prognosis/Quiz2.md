## 1. Which decision boundary corresponds to the following decision tree?
## In the options, red indicates high risk, blue indicates low risk.

## 2. True or False: A tree of depth 1 is more expressive than a classical linear model.
## A. False

## 3. One way to aggregate predictions from multiple trees is by a majority vote. Using this aggregation rule, select the prediction of the following trees on the data point (x=4, y=7, z=2):
## A. Low risk

## 4. You’ve fit a random forest of 10 trees with max depth 20. Your training ROC is 0.99 and test ROC is 0.54. Which of the following is NOT a reasonable thing to try?
## A. Increasing the max depth

## 5. True or False: When your data is missing at random, then whether or not you are missing a covariate is completely independent of your outcome.
## HINT: the data is "missing at random" and not "missing completely at random".
## A. False

## 6. When is complete case analysis least likely to bias your model?
## A. Data is missing completely at random.
## Data is missing not at random
## Data is missing at random
## Data is missing completely at random.

## 7. You have created a model using mean imputation. At test time, you should fill in missing values with:
## A. Mean from the train data?

## 8. Let’s say blood pressure (BP) measurements are more likely to be missing among young people, who generally have lower blood pressure. You use mean imputation to train your model. Which option correctly characterizes the mean BP (after imputation) in your training dataset?
## A. It is higher than the true mean.

## 9. You have trained the following tree and want to make a prediction on someone, but all you know is they are 40 years old, and do not have their blood pressure.
## A. Low Risk

## 10. Assume you have missing data on one of your features, and are considering two options:
Option 1: Drop the feature that has missing values and fit a linear regression on the remaining features.
Option 2: Use imputation on the feature that has missing values, and fit a linear regression on all features.
True or False: "Both options have the same performance".
## False
