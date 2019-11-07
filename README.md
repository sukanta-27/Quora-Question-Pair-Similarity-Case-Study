# Quora-Question-Pair-Similarity-Case-Study
This is my attempt on solving the Quora Question Pair Similarity Problem that was hosted as a competition on Kaggle. 
**Source**: https://www.kaggle.com/c/quora-question-pairs

# The Problem Statement:
Identify which questions asked on Quora are duplicates of questions that have already been asked. Doing so will make it easier to find high quality answers to questions resulting in an improved experience for Quora writers, seekers, and readers.

## Description:
Quora is a place to gain and share knowledge—about anything. It’s a platform to ask questions and connect with people who contribute unique insights and quality answers. This empowers people to learn from each other and to better understand the world.

Over 100 million people visit Quora every month, so it's no surprise that many people ask similarly worded questions. Multiple questions with the same intent can cause seekers to spend more time finding the best answer to their question, and make writers feel they need to answer multiple versions of the same question. Quora values canonical questions because they provide a better experience to active seekers and writers, and offer more value to both of these groups in the long term.

## Data Overview
- Data will be in a file Train.csv
- Train.csv contains 5 columns : qid1, qid2, question1, question2, is_duplicate
- Size of Train.csv - 60MB
- Number of rows in Train.csv = 404,290

## Type of Machine Leaning Problem
It is a binary classification problem, for a given pair of questions we need to predict if they are duplicate or not.

## Performance Metric
Source: https://www.kaggle.com/c/quora-question-pairs#evaluation

Metric(s):
log-loss : https://www.kaggle.com/wiki/LogarithmicLoss
Binary Confusion Matrix

## Final Logloss acheived in my case study:
The best logloss that I acheived by applying various models is ***0.334***
