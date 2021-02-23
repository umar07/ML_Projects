# Metals and rocks classification
## About the dataset-
This database contains 60 attributes, with 208 total instances. Each pattern is a set of 60 numbers in the range 0.0 to 1.0. The target label associated with each record contains the letter "R" if the object is a rock and "M" if it is a mine (metal cylinder). The task is to train a network to discriminate between sonar signals bounced off a metal cylinder and those bounced off a roughly cylindrical rock.
[Dataset Link](http://archive.ics.uci.edu/ml/datasets/connectionist+bench+(sonar,+mines+vs.+rocks))

## Algorithms used-
* Logistic Regression
* Linear Discriminant Analysis
* K Neighors Classifier
* Decision Tree Classifier
* Gaussian Naive Bayes
* Support Vector Machine

## Accuracy result-
KNN model
accuracy = 0.83
f1_score = 0.82 (macro-avg)

## Result after Hyperparameter tuning-
Best: 0.850000 using {'n_neighbors': 1} in KNN model
