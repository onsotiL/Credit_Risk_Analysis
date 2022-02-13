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

- The balanced accuracy score is about 65%.
- The high risk precision is about 1% only with  a recall of 69%  and F1 of only 2% .
- Its low risk precision is almost at 100% with a recall of 59%.

---
### SMOTE model
![image](https://user-images.githubusercontent.com/90416094/153759559-82197a1f-6b8e-47fa-bc38-a5af01cc430d.png)

- The balanced accuracy score also about 65%.
- The high_risk precision is about 1% only with 69% recall and F1 of 2% only.
- Its low risk precision is almost 100% with a recall of 59%.


---

### ClusterCentroids model

### ClusterCentroids model/Undersampling
![image](https://user-images.githubusercontent.com/90416094/153759649-fc84d561-77cf-4226-8420-ad5ffc2980e9.png)

- The balanced accuracy score is 54%.
- The high_risk precision is still 1% with 69% sensitivity and a F1 of 1%.
- The low_risk sensitivity is  40%.
---

### Balanced Random Frorest Classifier
![image](https://user-images.githubusercontent.com/90416094/153759881-5a710e25-cc4b-49ee-a5ff-32ff24a71109.png)

- The balanced accuracy score went up to about 79%.
- The high_risk precision is still low at 3% only with 70% recall and F1 of only 6%.
- The low_risk recall is now 87% with 100% presicion.

---

### Easy ensemble AdaBoost Classifier
![image](https://user-images.githubusercontent.com/90416094/153759956-93c85b4c-a4b8-4448-9857-91a4a55d6dbc.png)

- The balanced accuracy score is very high at about 93%.
- The high risk precision is at 9%  with a  92% recall and F1 of 16%.
- The low risk precision is at 100% with the recall at 94%.

----

## Summary:

The EasyEnsembleClassifier model shows a recall of 92%  and therefor detects almost all high risk credit compared to the other models .It also yeided the best results with an accuracy rate of 93%
