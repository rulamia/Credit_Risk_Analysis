# Credit Risk Analysis

## Overview of the Analysis
> In this analysis, we used machine learning to decide if a credit card application is a high or low risk for the creditor. We used resampling models and ensamble classifiers. 
## Results

### Naive Random Oversampling: 
> Balance Accuracy: 63%
#### High Risk:
> - Presision: 1%
> - Recall: 57%
#### Low Risk:
> - Presision: 100% 
> - Recall: 68%

![Naive Random Oversampling](https://github.com/rulamia/Credit_Risk_Analysis/blob/main/Resources/Naive%20Random%20Oversampling.PNG)

### SMOTE Oversampling: 
> Balance Accuracy: 63%
#### High Risk:
> - Presision: 1%
> - Recall: 62%
#### Low Risk:
> - Presision: 100%
> - Recall: 63%

![SMOTE Oversampling](https://github.com/rulamia/Credit_Risk_Analysis/blob/main/Resources/SMOTE%20Oversampling.PNG)

### Undersampling: 
> Balance Accuracy: 59%
#### High Risk:
> - Presision: 1%
> - Recall: 61%
#### Low Risk:
> - Presision: 100%
> - Recall: 57%

![Undersampling](https://github.com/rulamia/Credit_Risk_Analysis/blob/main/Resources/Undersampling.PNG)

### Combination (Over and Under) Sampling: 
> Balance Accuracy: 62%
#### High Risk:
> - Presision: 1%
> - Recall: 69%
#### Low Risk:
> - Presision: 100%
> - Recall: 55%

![Combination Over and Under Sampling](https://github.com/rulamia/Credit_Risk_Analysis/blob/main/Resources/Combination%20Over%20and%20Under%20Sampling.PNG)

### Balanced Random Forest Classifier: 
> Balance Accuracy: 79%
#### High Risk:
> - Presision: 3%
> - Recall: 70%
#### Low Risk:
> - Presision: 100%
> - Recall: 87%

![Balanced Random Forest Classifier](https://github.com/rulamia/Credit_Risk_Analysis/blob/main/Resources/Balanced%20Random%20Forest%20Classifier.PNG)

### Easy Ensemble AdaBoost Classifier: 
> Balance Accuracy: 93%
#### High Risk:
> - Presision: 9%
> - Recall: 92%
#### Low Risk:
> - Presision: 100%
> - Recall: 94%

![Easy Ensemble AdaBoost Classifier](https://github.com/rulamia/Credit_Risk_Analysis/blob/main/Resources/Easy%20Ensemble%20AdaBoost%20Classifier.PNG)


## Summary
> Based n the results shiwn above, Easy Ensemble AdaBoost Classifier was the most accurate model that we used. All metrics that were listed were the highest using that model. For the most accurate prediction, I would use Easy Ensemble AdaBoost Classifier based on the above metrics. 
