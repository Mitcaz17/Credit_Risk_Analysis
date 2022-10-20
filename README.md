# Credit_Risk_Analysis


## Overview of the loan prediction risk analysis:

The purpose of this analysis is to be able to deternine the ammount and percentage of loans that are low risk and high risk loans

## Results:

### RandonOverSampler

                   pre       rec       spe        f1       geo       iba       sup

  high_risk       0.03      0.82      0.84      0.06      0.83      0.69       101
   low_risk       1.00      0.84      0.82      0.91      0.83      0.69     17104

avg / total       0.99      0.84      0.82      0.91      0.83      0.69     17205

### Smote

                   pre       rec       spe        f1       geo       iba       sup

  high_risk       0.04      0.82      0.87      0.07      0.84      0.71       101
   low_risk       1.00      0.87      0.82      0.93      0.84      0.72     17104

avg / total       0.99      0.87      0.82      0.92      0.84      0.72     17205

### UnderSampling 

                   pre       rec       spe        f1       geo       iba       sup

  high_risk       0.02      0.88      0.76      0.04      0.82      0.68       101
   low_risk       1.00      0.76      0.88      0.86      0.82      0.66     17104

avg / total       0.99      0.76      0.88      0.86      0.82      0.66     17205

### Smoteen


                   pre       rec       spe        f1       geo       iba       sup

  high_risk       0.04      0.82      0.87      0.07      0.84      0.71       101
   low_risk       1.00      0.87      0.82      0.93      0.84      0.72     17104

avg / total       0.99      0.87      0.82      0.92      0.84      0.72     17205


### BalancedRandomForestClassifier

BalancedRandomForestClassifer
                   pre       rec       spe        f1       geo       iba       sup

  high_risk       0.03      0.63      0.88      0.06      0.75      0.55       101
   low_risk       1.00      0.88      0.63      0.94      0.75      0.57     17104

avg / total       0.99      0.88      0.64      0.93      0.75      0.57     17205

### Easy Ensemble AdaBoost Classifier

                   pre       rec       spe        f1       geo       iba       sup

  high_risk       0.09      0.92      0.94      0.16      0.93      0.87       101
   low_risk       1.00      0.94      0.92      0.97      0.93      0.87     17104

avg / total       0.99      0.94      0.92      0.97      0.93      0.87     17205

## Summary:

Looks like that between all of the models, none of them resulted to be completely accurate.

With that being said in my opinion the one that ended up being the most accurate was the Random Over Sampler 