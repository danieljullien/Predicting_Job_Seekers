# Predicting Job Seekers in an Imbalanced Dataset

## Overview 
In this project we will study a dataset of Data Scientists, doing some necessary data cleaning, an exploratory data analysis and finally a model to predict whether they are looking for job change or not. This is an interesting use of Data Science for the Human Ressources Team.

We will be working with an imbalanced dataset (which will be observed later) and when that is the case most machine learning techniques will almost ignore the minority class, classifying most of the data to the majority class. This is an issue, as typically it is performance on the minority class that is most important. We will explore ways to work with this kind of dataset as well.

### Machine Learning Models Applied:
- Logistic Linear Regression
- KNN
- Logistic Regression
- Decision tree
- Random forest
- Ada Boost
- Gradient Boosting

### Oversampling Techniques
- SMOTE
- Borderline-SMOTE

## Business Problem:
A company which wants to hire data scientists among people who successfully pass some courses conducted by the company. Howerver, many people signup for their training. Therefore, the HR Team wants identify which of these candidates are truely looking for a new employment as it will reduce the cost and time of this selection as well as possibly increase the quality of training or planning the courses, being able to categorize the candidates and better instruct them during courses.

There are some information avialable related to demographics, education and experience, obtained from candidates signup and courses enrollment.

## Problem Statment
HR wants to understand the factors that lead a person to leave current job. They are also interested in a model that can classify the candidates in job seekers or non-seekers.

## Data:
- enrollee_id : Unique ID for candidate
- city: City code
- city_ development _index : Developement index of the city (scaled)
- gender: Gender of candidate
- relevent_experience: Relevant experience of candidate
- enrolled_university: Type of University course enrolled if any
- education_level: Education level of candidate
- major_discipline :Education major discipline of candidate
- experience: Candidate total experience in years
- company_size: No of employees in current employer's company
- company_type : Type of current employer
- lastnewjob: Difference in years between previous job and current job
- training_hours: training hours completed
- target: 0 – Not looking for job change, 1 – Looking for a job change

Dataset available in: https://www.kaggle.com/arashnic/hr-analytics-job-change-of-data-scientists

