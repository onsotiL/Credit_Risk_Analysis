# Credit_Risk_Analysis
## Overview 
In this project, Python is used to build machine learning models for predicting credit risk.
The following procedures were used to build and evaluate the effectiveness of the models:

- Oversampling the data using the RandomOverSampler and SMOTE algorithms.
- ClusterCentroids algorithm to demonstratete Undersampling
- Combination (Over and Under) Sampling using the SMOTEENN algorithm.
- Compare two ensemble algorithms (BalancedRandomForestClassifier and EasyEnsembleClassifier)to determine which algorithm results in the best performance.

## Results
### RandomOverSampler model
![image](https://user-images.githubusercontent.com/90416094/153759518-f0d3cc74-8948-425f-a5da-c12acb1eea66.png)

- The balanced accuracy score for this model is about 65%.
- The precision and recall scores 1% with 62% sensitivity making a F1 of 2%
- Precision is almost 100% with a sensitivity of 68%.

---
### SMOTE model
![image](https://user-images.githubusercontent.com/90416094/153759559-82197a1f-6b8e-47fa-bc38-a5af01cc430d.png)

- The balanced accuracy score is also 64%.
- The high_risk precision is about 1% only with 63% sensitivity and a F1 of 2% only.
- Its precision is almost 100% with a sensitivity of 66%.
---

### ClusterCentroids model

### ClusterCentroids model/Undersampling
![image](https://user-images.githubusercontent.com/90416094/153759649-fc84d561-77cf-4226-8420-ad5ffc2980e9.png)

- The balanced accuracy score is 52%.
- The high_risk precision is still 1% with 63% sensitivity and a F1 of 1%.
- The low_risk sensitivity is only 40%.
---

### Balanced Random Frorest Classifier
![image](https://user-images.githubusercontent.com/90416094/153759881-5a710e25-cc4b-49ee-a5ff-32ff24a71109.png)

- The balanced accuracy score went up to about 79%.
- The high_risk precision is still low at 4% only with 67% sensitivity which makes a F1 of only 7%.
- Due to a lower number of false positives, the low_risk sensitivity is now 91% with 100% presicion.

---

### Easy ensemble AdaBoost Classifier
![image](https://user-images.githubusercontent.com/90416094/153759956-93c85b4c-a4b8-4448-9857-91a4a55d6dbc.png)

- The balanced accuracy score is very high at about 93%.
- The high_risk precision is at a low of 7%  with a h 91% sensitivity which makes a F1 of only 14%.
- As a result of low false positives, the low_risk sensitivity is  94% with 100% presicion.

The "High Risk precision rate increased to 9% with the recall at 92% giving this model an F1 score of 16%.
"Low Risk" still had a precision rate of 100% with the recall now at 94%.

----

## Summary:
The EasyEnsembleClassifer model yielded the best results with an accuracy rate of 93.2%. The sensitivity(recall) compared to the other models was also the highest at 92% compared to the other models
