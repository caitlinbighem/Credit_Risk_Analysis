# Credit Risk Analysis

## Overview
Machine learning can be utilized to predict credit risk. By utilizing it, it will not only provide a quicker and more reliable loan experience but will also lead to a more accurate identification of good candidates for loans, which will lead to lower default rates. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, different techniques need to be employed to train and evaluate models with unbalanced classes. Numerous supervised machine learning models or algorithms have been built and evaluated to predict credit risk. 

## Results

![Classification Report Imbalanced 1](https://github.com/caitlinbighem/Credit_Risk_Analysis/blob/main/Resources/Screenshot%201.PNG)

* Balanced Accuracy Score: 62%
* Precision High Risk: 1%
* Precision Low Risk: 100%
* Recall High Risk: 72% 
* Recall Low Risk: 54%

**Confusion Matrix**
|             | Predicted True  | Predicted False | 
|-------------|------|------|
| Actually True | 70 | 31 |
| Actually False | 6711 | 10393 |


![Classification Report Imbalanced 2](https://github.com/caitlinbighem/Credit_Risk_Analysis/blob/main/Resources/Screenshot%202.PNG)

* Balanced Accuracy Score: 50%
* Precision High Risk: 1%
* Precision Low Risk: 100%
* Recall High Risk: 59% 
* Recall Low Risk: 43%

**Confusion Matrix**
|             | Predicted True  | Predicted False | 
|-------------|------|------|
| Actually True | 64 | 37 |
| Actually False | 5291 | 11813 |


![Classification Report Imbalanced 3](https://github.com/caitlinbighem/Credit_Risk_Analysis/blob/main/Resources/Screenshot%203.PNG)

* Balanced Accuracy Score: 65%
* Precision High Risk: 1%
* Precision Low Risk: 100%
* Recall High Risk: 63% 
* Recall Low Risk: 66%

**Confusion Matrix**
|             | Predicted True  | Predicted False | 
|-------------|------|------|
| Actually True | 70 | 31 |
| Actually False | 10340 | 6764 |


![Classification Report Imbalanced 4](https://github.com/caitlinbighem/Credit_Risk_Analysis/blob/main/Resources/Screenshot%204.PNG)

* Balanced Accuracy Score: 66%
* Precision High Risk: 1%
* Precision Low Risk: 100%
* Recall High Risk: 66% 
* Recall Low Risk:67%

**Confusion Matrix**
|             | Predicted True  | Predicted False | 
|-------------|------|------|
| Actually True | 72 | 29 |
| Actually False | 7195 | 9909 |


![Classification Report Imbalanced 5](https://github.com/caitlinbighem/Credit_Risk_Analysis/blob/main/Resources/Screenshot%205.PNG)

* Balanced Accuracy Score: 78%
* Precision High Risk: 4%
* Precision Low Risk: 100%
* Recall High Risk: 67% 
* Recall Low Risk: 91%

**Confusion Matrix**
|             | Predicted True  | Predicted False | 
|-------------|------|------|
| Actually True | 71 | 30 |
| Actually False | 2153 | 14951 |


![Classification Report Imbalanced 6](https://github.com/caitlinbighem/Credit_Risk_Analysis/blob/main/Resources/Screenshot%206.PNG)

* Balanced Accuracy Score: 84%
* Precision High Risk: 7%
* Precision Low Risk: 100%
* Recall High Risk: 90% 
* Recall Low Risk: 94%

**Confusion Matrix**
|             | Predicted True  | Predicted False | 
|-------------|------|------|
| Actually True | 93 | 8 |
| Actually False | 983 | 16121 |



## Summary
Multiple machine learning models were employed while determining which would be the most effective and efficient at predicting credit risk. By reviewing each model and the results they have produced, all can be evaluated for accuracy, precision and sensitivity. The confusion matrix accompanying each model can be calculated with the following table: 


**Confusion Matrix**
|             | Predicted True  | Predicted False | 
|-------------|------|------|
| Actually True | TP | FN |
| Actually False | FP | TN |

* Accuracy = (True Positives (TP) + True Negatives (TN)) / Total
* Precision = True Positives (TP) / (True Positives (TP) + False Positives (FP))
* Sensitivity = True Positives (TP) / (True Positives (TP) + False Negatives (FN)) 


The analysis shown above suggests that the precision scores for each model are overfit. While a good balance of recall and precision is needed to have an effective model, most of the above models do not have this balance. However, the model indicated in “Classification Report Imbalanced 6” is recommended for future use, namely due to its high balanced accuracy score, as well as its balance of recall and precision scores. 
