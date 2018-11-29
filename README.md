# Overview

The goal of this project, is to use data from accelerometers on the belt, forearm, arm, and dumbell of 6 participants that were asked to perform barbell lifts correctly and incorrectly in 5 different ways to predict the manner in which they did the exercise(This is the "classe" variable in the training set.)

## Background

Using devices such as Jawbone Up, Nike FuelBand, and Fitbit it is now possible to collect a large amount of data about personal activity relatively inexpensively. These type of devices are part of the quantified self movement - a group of enthusiasts who take measurements about themselves regularly to improve their health, to find patterns in their behavior, or because they are tech geeks. One thing that people regularly do is quantify how much of a particular activity they do, but they rarely quantify how well they do it. 
## Summary of findings

To predict the __classe__ variable, we tried predicting with randomforests. RandomForests method 

1. Bootstrap samples
2. At each split, bootstrap variables
3. Grow multiple trees and vote

Although this method is slow and prone to overfitting, it is has a high accurary rate. 

We fitted 52 feautures as predictors for the ___classe___ variable. The model final model had acuracy of about 98% which we are very comfortable with. Testing the model on our testing samples, the model was able to predict the classe of the barlifts with an accuracy of 99%

The details of analysis and conclusions made can be found [here](https://sherrypha.github.io/Practical-Machine-Learning/Prediction_Assignment.html)
