# Decision-Trees

Decision Trees are a non-parametric supervised learning method used for [classification](https://www.geeksforgeeks.org/ml-classification-vs-regression/) and [regression](https://www.geeksforgeeks.org/ml-classification-vs-regression/). The goal is to create a model that predicts the value of a target variable by learning simple decision rules inferred from the data features.


Dcision trees learn from data to approximate a sine curve with a set of if-then-else decision rules. The deeper the tree, the more complex the decision rules and the fitter the model.


## Clssification 

DecisionTreeClassifier is a class capable of performing multi-class classification on a dataset.

DecisionTreeClassifier takes as input two arrays: an array X, sparse or dense, of size [n_samples, n_features] holding the training samples, and an array Y of integer values, size [n_samples], holding the class labels for the training samples

I can also export the tree in Graphviz format using the export_graphviz exporter. 
 installed with **conda install python-graphviz**
