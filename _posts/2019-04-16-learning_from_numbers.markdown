---
layout: post
title:      "Learning from numbers"
date:       2019-04-16 17:29:55 +0000
permalink:  learning_from_numbers
---


This was an interesting project.  As a person who likes numbers and earning money, I appraoched this project as an opportunist.  I wanted to see if there were effective insights I could gather from the data. 
The two things I knew about relistate before I started Flatiron were 1. Size matters 2. Location, Location , Location
Using linear regression and size as a predictor of housing prices is pretty simple to set up.  Price = m x Size + b.  Simple, but how do I incorperate the other important factor, location, into this equation?  That was the challenge of this project.  
The challenge is - location is a category.  There isnt a linear relationship between location and price.  But location can tell us something else - the AVERAGE price of the houses per zipcode.  I got inspired by watching sklearn videos and learning about KNN.  I didn't use KNN - but I made a ranking system based on the average price per zipcode.  I binned up my houses into 6 different parts based on the average housing price distribution per zipcode.  I then created a pandas series based on the zipcode ranks and added it to my database.  I WAS SO HAPPY.  Linear regression only works well when the variables are independent.  Multicolinearity will screw up your model when you have multiple predictors that are all highly correlated with eachother.  My neighborhood ranking system was not highly correlated with housing size - this is what made my model give me a good R2 value. 
So zipcode was important for the model, but when I looked at the houses resold - it gave me insight into why certain people made money and lost money.  The lesson I learned from the data is -If you want to flip a house, it's better to buy a small house for cheap in a good neighborhood, then it is to buy a big house in a bad neighborhood.  A person made over half a million dollars by doing just that - and another person lost 40 grand by making the 2nd mistake.
