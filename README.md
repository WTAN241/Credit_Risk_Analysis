# Credit_Risk_Analysis
## Overview of the analysis
In this analysis, we have applied machine learning to solve the real-world challenge of credit card risk. Various machine learning models have been used for the credit card dataset. The purpose of this analysis is to evaluate the performance of these models and make a recommendation on whether they should be used to predict credit risk.

## Results
### Naive Random Oversampling
1. The balanced accuracy score is about 0.648 when using the naive random oversampling

![naive_random_oversampling_bas](https://github.com/WTAN241/Credit_Risk_Analysis/blob/main/Resources/naive_random_oversampling_bas.PNG)

2. The precision for prediction of low credit risk is much higher than it is for predicting high credit risk

3. The recall (sensitivity) for predicting credit risk are in line with each other

4. The higher precision for low risk is reflected in the increase of F1 score as well

![naive_random_oversampling_report](https://github.com/WTAN241/Credit_Risk_Analysis/blob/main/Resources/naive_random_oversampling_report.PNG)

### SMOTE Oversampling
1. The balanced accuracy score is about 0.663 when using the SMOTE oversampling

![smote_oversampling_bas](https://github.com/WTAN241/Credit_Risk_Analysis/blob/main/Resources/smote_oversampling_bas.PNG)

2. The precision for prediction of low credit risk is much higher than it is for predicting high credit risk

3. The recall (sensitivity) for predicting credit risk are in line with each other

4. The higher precision for low risk is reflected in the increase of F1 score as well

5. The F1 score increase is higher than the F1 score increase in the naive random oversampling

![smote_oversampling_report](https://github.com/WTAN241/Credit_Risk_Analysis/blob/main/Resources/smote_oversampling_report.PNG)

### Undersampling
1. The balanced accuracy score is about 0.663 when using the undersampling machine learning method

![undersampling_bas](https://github.com/WTAN241/Credit_Risk_Analysis/blob/main/Resources/undersampling_bas.PNG)

2. The precision for prediction of low credit risk is much higher than it is for predicting high credit risk

3. The recall (sensitivity) for predicting low credit risk is slightly higher than high credit risk

4. The higher precision for low risk is reflected in the increase of F1 score as well

5. The F1 score increase is lower than the F1 score increase in the SMOTE and naive random oversampling

![undersampling_report](https://github.com/WTAN241/Credit_Risk_Analysis/blob/main/Resources/undersampling_report.PNG)

### Combination Sampling
1. The balanced accuracy score is about 0.545 when using the combination sampling

![combination_bas](https://github.com/WTAN241/Credit_Risk_Analysis/blob/main/Resources/combination_bas.PNG)

2. The precision for prediction of low credit risk is much higher than it is for predicting high credit risk

3. The recall (sensitivity) for predicting high credit risk is slightly higher than high credit risk

4. The higher precision for low risk is reflected in the increase of F1 score as well

![combination_report](https://github.com/WTAN241/Credit_Risk_Analysis/blob/main/Resources/combination_report.PNG)

### Balanced Random Forest Classifier
1. The balanced accuracy score is about 0.789 when using the balanced random forest classifier

![balanced_rf_bas](https://github.com/WTAN241/Credit_Risk_Analysis/blob/main/Resources/balanced_rf_bas.PNG)

2. The precision for prediction of low credit risk is much higher than it is for predicting high credit risk

3. The recall (sensitivity) for predicting low credit risk is slightly higher than high credit risk

4. The higher precision for low risk is reflected in the increase of F1 score as well

![balanced_rf_report](https://github.com/WTAN241/Credit_Risk_Analysis/blob/main/Resources/balanced_rf_report.PNG)

### Easy Ensemble AdaBoost Classifier
1. The balanced accuracy score is about 0.932 when using the easy ensemble adaboost classifier

![eec_bas](https://github.com/WTAN241/Credit_Risk_Analysis/blob/main/Resources/eec_bas.PNG)

2. The precision for prediction of low credit risk is much higher than it is for predicting high credit risk

3. The recall (sensitivity) for predicting low credit risk is slightly higher than high credit risk

4. The higher precision for low risk is reflected in the increase of F1 score as well

![eec_report](https://github.com/WTAN241/Credit_Risk_Analysis/blob/main/Resources/eec_report.PNG)

## Summary

After evaluating the balanced accuracy scores and classification reports from the six machine learning models listed above, I recommend using the easy ensemble adaboost classifier. First, the EEC model has the highest balanced accuracy score among the six models. Second, it has the highest recall (sensitivity) for predicting high risk credit card transactions. As a result, the EEC model would be the most effective among the six models in catching high credit risk transactions.