# Results

## Overview

This section reports the results of classifying mushrooms into edible and not edible by appllying several classifiers that include logistic regression, KNN, decision tree, random forest, SVC, naive Bayes and neural network.

The analysis is described in the [previous section](https://eagronin.github.io/mushroom-classification-analyze).

This project is based on materials from Applied Machine Learning in Python by University of Michigan on Coursera

The analysis for this project was performed in Python.

## Results and Discussion

The results are reported along with visualizations of decision boundary and decision probabilities for each classifier fitted in the [previous section](https://eagronin.github.io/mushroom-classification-analyze).  All the classifiers are comparable in terms of their performance on the test data, with the accuracy score ranging from 0.87 to 0.94, and random forest generating the highest score of 0.94.

The plot of the target as a function of the first two principal components for the training data is shown below:

![](https://github.com/eagronin/mushroom-classification-report/blob/master/pca.png?raw=true)

The following plots are the decision boundary and decision probabilities for each classifier along with the accuracy score measured using the test data:

![](https://github.com/eagronin/mushroom-classification-report/blob/master/logit.png?raw=true)
![](https://github.com/eagronin/mushroom-classification-report/blob/master/knn.png?raw=true)
![](https://github.com/eagronin/mushroom-classification-report/blob/master/tree.png?raw=true)
![](https://github.com/eagronin/mushroom-classification-report/blob/master/forest.png?raw=true)
![](https://github.com/eagronin/mushroom-classification-report/blob/master/svc.png?raw=true)
![](https://github.com/eagronin/mushroom-classification-report/blob/master/naive.png?raw=true)
![](https://github.com/eagronin/mushroom-classification-report/blob/master/mlp.png?raw=true)

Previous step: [Analysis](https://eagronin.github.io/mushroom-classification-analyze)
