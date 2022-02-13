# Credit_Risk_Analysis
Overview 
In this project, Python is used to build machine learning models for predicting credit risk.
The following procedures were used to build and evaluate the effectiveness of the models:
- oversample the data using the RandomOverSampler and SMOTE algorithms.
- ClusterCentroids algorithm to demonstratete Undersampling
- Combination (Over and Under) Sampling using the SMOTEENN algorithm.
- Compare two ensemble algorithms (BalancedRandomForestClassifier and EasyEnsembleClassifier)to determine which algorithm results in the best     performance.
RandomOverSampler model
- The balanced accuracy score for this model is about 65%.
- the precision and recall scores 1% with 62% sensitivity which makes a F1 of 2% only.
- precision is almost 100% with a sensitivity of 68%.
. SMOTE model

-The balanced accuracy score is 64%.
-The high_risk precision is about 1% only with 63% sensitivity which makes a F1 of 2% only.
- its precision is almost 100% with a sensitivity of 66%.
ClusterCentroids model/Undersampling
-Here the balanced accuracy score is 52%.
-The high_risk precision is still 1% with 63% sensitivity which makes a F1 of 1%.
-the low_risk sensitivity is only 40%.
1.	Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
