---
layout: post
title:      "Machine Learning"
date:       2019-12-13 21:48:01 +0000
permalink:  machine_learning
---


Machine learning involves a class of algorithms  that automate model building.  This is based on the idea that machines can regonize patterns and make predictions with little human intervention.  Where as statistics is used to gain insight from information based on interpretable results.  Machine learning is more like a soup of data - you dont really care about the insight you get from the information - often times it's near impossible to make an easily interpretable ML model.  ML models are good at making predictions however.  But as with every sort of ML model, trash going in - trash going out.  
For my gender predicting project, I was deciding between what ML model to use.  Random Forest - which builds decision trees independently and averages the results at the end - or Gradient Boosted Trees which boosts the weak predictors as it goes along and totals the results at the end.. or maybe KNN or Logistic Regression?  Well to find out which was the best - I used a ML pipeline which trys each model with different tuning parameters and then shows the results.  This worked, but none of my results gave me an accuracy near 80 or an f1 score that made me confident in the model.
So in the end, I used a voting classifier which weighed the reults of each model and 'voted' based on those results.  This gave me an accuracy of 85% and an F1 of 91%.  
Overall I was happy with the results - there was a class imbalance issue because more men were arrested than women - but, I felt if I did any upsampling or downsampling - it would scew the results the other way.  The bias inherited in these models isn't as big of an issue because men get arrested more than women anyways - so the same distribution will occur.
