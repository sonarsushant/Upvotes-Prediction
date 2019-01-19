# Upvotes Prediction

This is a problem statement of [Enigma CodeFest Machine Learning](https://datahack.analyticsvidhya.com/contest/enigma-codefest-machine-learning/) organized by Analytics Vidhya. 

## Problem Statement:
An online question and answer platform has hired you as a data scientist to identify the best question authors on the platform. This identification will bring more insight into increasing the user engagement. Given the tag of the question, number of views received, number of answers, username and reputation of the question author, the problem requires you to predict the upvote count that the question will receive.

## Dataset:
The dataset contains 330045 rows and 7 columns.

| Variable | Definition |
| --- | --- |
| ID | Question ID |
| Tag | Anonymised tags representing question category |
| Reputation | Reputation score of question author |
| Answers | Number of times question has been answered |
| Username | Anonymised user id of question author |
| Views | Number of times question has been viewed | 
| Upvotes | (Target) Number of upvotes for the question |

## Solution
I have done exploratory danalysis of the dataset followed by training a machine learning model to predict Upvotes.

Models Used:
1. Linear Regression
2. XGBoost
3. Stacking of Linear Regression and XGBoost
