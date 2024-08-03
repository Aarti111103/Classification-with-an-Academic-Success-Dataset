# Kaggle Competition: Classification with an Academic Success Dataset
This repository contains the code and documentation for my participation in the Kaggle competition "Classification with an Academic Success Dataset." In this competition, I used a logistic regression model to predict academic risk for students in higher education.

## Overview
The 2024 Kaggle Playground Series continues with the "Classification with an Academic Success Dataset" competition, designed to help participants practice their machine learning skills using an approachable and interesting dataset.

## Goal
The primary objective of this competition is to predict the academic risk of students in higher education. This involves classifying students into categories based on their likelihood of academic success or failure. By accurately predicting these outcomes, educational institutions can take proactive measures to support at-risk students and improve overall academic performance.

## Timeline
Start Date: June 1, 2024
Entry Deadline: June 30, 2024
Team Merger Deadline: June 30, 2024
Final Submission Deadline: June 30, 2024
All deadlines are at 11:59 PM UTC on the corresponding day unless otherwise noted. The competition organizers reserve the right to update the contest timeline if they deem it necessary.

## Dataset Description
The dataset for this competition includes both training and test sets. Feature distributions are similar to the original dataset but not exactly the same. You may use the original dataset to explore differences and potentially improve model performance.

Train Dataset (train.csv): Contains the training data with various features and a categorical target labeled Target.

Test Dataset (test.csv): Used for making predictions. Participants must predict the Target for each row.

Sample Submission (sample_submission.csv): A template to guide the format for final submissions.

## Submission File
For each ID row in the test set, you must predict the class value of the Target, which is a categorical academic risk assessment. The file should contain a header and be formatted as follows:

id,Target

76518,Graduate

76519,Graduate

76520,Graduate

...

## Logistic Regression Model
I chose a logistic regression model for predictions due to its simplicity and effectiveness in binary classification tasks. The following steps outline the approach:

Data Preprocessing: Cleaning and preparing the data for modeling.

Model Training: Using logistic regression to train on the training dataset.

Prediction: Generating predictions on the test dataset.

Submission: Creating a submission file in the required format.

## Conclusion
Participating in this competition was a great opportunity to enhance my skills in data science and machine learning. The logistic regression model provided valuable insights into predicting academic risk, and I look forward to applying these techniques to future projects.

