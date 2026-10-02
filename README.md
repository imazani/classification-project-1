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
| marital | categorical | marital status | note divorced mean divorced or widowsed |
| education | categorical | costomer highest education  level | contains uknowns |
| balance | numeric | yearly account balance | inspect distribution |
| housing | binary | has housing loan |   |
| loan | binary | has personal loan |   |
| contact | categorical | contact communication type | contains unknowns |
| day | numeric | last contact day of the month |   |
| month | categorical | last contact month of year |  |
| duration | numeric | las contact duration in seconds |  |
| campaign | numeric | number of contacts performed during campaign for this client | includes last contact |
| pdays | numeric | numer of days that passed by after the client was last contacted from a previous campaign | -1 means client was not previously contacted |
| previous | numeric | numer of contacts performed before this campaign and for this client |  |
| poutcome | categorical | outcome of previous marketing campaign | contains uknowns |
| y | binary | subscribed to depostic | target|
