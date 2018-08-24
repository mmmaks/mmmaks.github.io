---
layout: post
title: Model evaluation error metrics
---

## Confusion matrix
NxN matrix, where N is the number of classes for classification.

![_config.yml]({{ site.baseurl }}/images/confusion.png)

* Accuracy: ratio of correct prediction vs total predictions
* Positive Predictive Value or Precision: ratio of correctly predicted positive case to total positive predictions
* Negative Predictive Value: ratio of correctly predicted negative case to total negative
predictions
* Sensitivity or Recall (True Positive rate): ratio of correctly positive prediction to actual
number of positives
* Specificity (false positive rate): ratio of correctly negative prediction to actual number of
negatives

![_config.yml]({{ site.baseurl }}/images/formula.png)

## ROC AUC
The ROC curve is the plot between sensitivity and (1- specificity)
![_config.yml]({{ site.baseurl }}/images/ROC.png)
Here different lines are for different model. Model W is better than X, model X is better than Y and so on.