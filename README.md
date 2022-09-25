# Predicting-the-Sale-Price-of-Bulldozers-using-Machine-Learning
his is a second project for my machine learning practice. If you have finished beginner projects, it is time to try this project.

Goal To predict the sale price of bulldozers

Date Started: Mon 25 Jul 2022

Date to go through till: Wed 10 Aug 2022

Status
(What I'm doing now)

Finished This Project.
Dependencies
Pandas
NumPy
Matplotlib
Sckikit-Learn
We're going to take the following approach:

Problem defination
Data
Evaluation
Features
Modelling
Experimentation
1. Problem defination
How well can we predict the future sale price of a bulldozer, given its characteristics and previous examples of how much similar bulldozers have been sold for?

2. Data
The data is downloaded from the Kaggle Bluebook for Bulldozers competition: https://www.kaggle.com/competitions/bluebook-for-bulldozers/data

There are three main datasets:

Train.csv is the training set, which contains data through the end of 2011.
Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.
Test.csv is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competition.
3. Evaluation
The evaluation metric for this competition is the RMSLE (root mean squared log error) between the actual and predicted auction prices.

For more on the evaluation of this project check: https://www.kaggle.com/competitions/bluebook-for-bulldozers/overview/evaluation

Note The goal for most regression evaluation metrics is to minimize the error. For example, our goal for this project will be to build a machine learning model which minimises RMSLE.
