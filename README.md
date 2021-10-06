# EE0005-Project
 A data science project for the course EE0005

## Dataset used

Fake Job Posting Prediction
https://www.kaggle.com/shivamb/real-or-fake-fake-jobposting-prediction


## Problem

Whats the are the important variables in deciding whether the job posting is fake? (Train a classification model)

## Intuitions in deciding fraudulent job postings

- Low edu requirement but high salary `["salary_range", "required_education"]`
- Null in most fields
- Most are full-time employment `["employment_type"]`