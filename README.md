# Bank Marketing Classification

## Project Goal

The goal is to build and evaluate binary classifications models that predict whether a bank costomer will subscribe to a term deposit following a marketing campaign.


## Data Set

Source: UCI Machine Learning Repository - Bank Marketing Dataset

Target:
- 'y = yes' customer will subscribe 
- 'y = no' costomer won't subscribe

## Initial Questions

- How imbalanced is the target?
- How do logistic regression, KNN, and simple decision tree compare?
- How do different classification thresholds affect flase positives and fase negatives?

## Data Dictionary

| Variable | Type | Meaning | Initial concerns |
| --- | --- | --- | --- |
| age | numberic | customer age | n/a |
| job | categorial | customer occupation | contains uknowns |
| balance | numeric | yearly account balance | inspect distribution |
| contanct | categorical | communcation type | ? |
| duraction | numeric | call duration | leakage? |
| y | binary | subscribed to depostic | target|
