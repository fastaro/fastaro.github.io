---
layout: post
title:      "Statistics vs Machine Learning"
date:       2019-12-13 18:15:59 -0500
permalink:  statistics_vs_machine_learning
---


Statistics is about what you can quantify. What can you say about your information and how confident are you about that statement?  This makes the interpretablility of your information curical.  The most intretable model is regression.  This is the model where ML and statistics cross the most.  In regression, we use a gradient to minimize a 'cost function' so the slope that goes through the points has the lowest error.   This is easily interpretable because we usually understand what those data points reprsent, and the slope is reasonable. 
For machine learning, we don't care how interpetable a model is, as long as it works.  A good metric for measuring how good a model is, is an ROC-AUC score.  This tells how good a model is at telling the difference between two things.  If the ROC-AUC score is 50%, this means your model is no better than a coin flip at guessing classes.  If your model has a score of 90% that means you model is performing very well.  ROC-AUC measures how much better your model is than random guessing.  
Machine learning can pick up patterns in information that is hard to find, and can improve themselves without human intervention.  
Statitics can unviel insight into information.  You may see a difference in two datasets - is this difference significant?  
Machine learning deals primairly with making predictions where as stastics is used for infrence about two or more variables.
Machine learning is all about the results and statistics is about the relationships between variables.
