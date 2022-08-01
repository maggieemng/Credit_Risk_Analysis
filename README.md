# Credit Risk Analysis
## OVERVIEW - Purpose of Analysis

The purpose of this project is to use imbalanced-learn and scikit-learn libraries to build and evaluate models with unbalanced classes using resampling. 

## RESULTS

### Naive Random Oversampling results: 
- Our balanced accuracy test it 67%, 
- the precision for the high_risk has a very low positivity at 1% and 
- the recall is 74%

### SMOTE oversampling results: 
- The accuracy score is 66.2%, 
- The precision for the high_risk loans has a low positvity again at 1% and 
- recall is 69% overall

### Undersampling results: 
- balanced accuracy score is 66.2% overall, 
- the precision is at 99% and 
- the recall is 41%

### Combination results: 
- balanced accuracy score is 54.7%,
- the precision is 99% and 
- the recall is 57% overall

### Balanced Random Forest Classifier results: 
- the accuracy score is 77.2%, 
- the precision is 99% and
- the recall is 88%

### Easy Ensemble AdaBoost Classifier results: 
- the accuracy score is 91.7%, 
- the precision is 99% and 
- the recall is 94%

## SUMMARY
The first four models were of undersampled, oversampled and did a combination of both to try and determine which model is best at predicting which loans are the highest risk. The next two models are resampling of the data using ensemble classifiers to try and predict which which loans are high or low risk. 
I recommend to use the ensemble classifiers instead of the other types of models because it has the best balance/average outcome for recall and precision. 
