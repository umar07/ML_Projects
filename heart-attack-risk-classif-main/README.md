# Heart attack risk classification
## About the dataset-
This database contains 76 attributes, but all published experiments refer to using a subset of 14 of them. In particular, the Cleveland database is the only one that has been used by ML researchers to
this date.The "target" field refers to the presence of heart disease in the patient. It is integer valued 0 = no/less chance of heart attack and 1 = more chance of heart attack.
[Dataset Link](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)

## Algorithms used-
* Logistic Regression
* Linear Discriminant Analysis
* K Neighors Classifier
* Decision Tree Classifier
* Gaussian Naive Bayes
* Support Vector Machine

## Accuracy result-
LDA model
accuracy = 0.74
f1_score = 0.73 (macro-avg)

## Result after Hyperparameter tuning-
Best score: 0.854667 using {'solver': 'svd'} in LDA model


