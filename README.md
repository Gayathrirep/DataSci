### Problem Description

This is the problem of a Shinkansen (Bullet-Trains) of Japan. They aim to determine the relative importance of each parameter with regards to their contribution to the passenger travel experience. Provided is a random sample of individuals who travelled using their train. The on-time performance of the trains along with the passenger’s information is published in the CSV file named ‘Traveldata_train’.  These passengers were later asked to provide their feedback on various parameters related to the travel along with their overall experience. These collected details are made available in the survey report CSV labelled ‘Surveydata_train’.

In the survey, a passenger was explicitly asked whether they were delighted with their overall travel experience and that is captured in the data of the survey report under the variable labelled ‘Overall_Experience’. 
 
### Problem Statement 
The objective of this exercise is to understand which parameters play an important role in swaying passenger feedback towards a positive scale. 
Goal:
The goal of the problem is to predict whether a passenger was delighted considering his/her overall travel experience of traveling in Shinkansen (Bullet Train). For each passenger id in the test set, you must predict the “Overall_Experience” level.

Dataset

The problem consists of 2 separate datasets: Travel data & Survey data. The Travel data has information related to passengers and the performance of the Train in which they traveled. The survey data is the aggregated data of surveys collected post-service experience. You are expected to treat both the datasets as raw data and perform any necessary cleaning/validation steps as required.

Metric to measure

Your score is the percentage of all correct predictions made by you. This is simply known as accuracy. The best accuracy is 1 whereas the worst is 0. It will be calculated as the total number of two correct predictions (True positive + True negative) divided by the total number of observations in the dataset.

Submission File Format:

You should submit a CSV file with exactly 35602 entries plus a header row.

The file should have exactly two columns

·         ID ( sorted in any order)

·         Overall_Experience (contains 0 & 1, 1 represents delighted)

Working with Data

Data has been split into two groups and provided in the module:

·         train dataset

·         test dataset 

The training set is used to build your machine learning model. For the training set, we provide the Overall_Experience level for each participant.

The test set should be used to see how well your model performs on unseen data. For the test set, it is your job to predict the “Overall Experience” level for each participant.
