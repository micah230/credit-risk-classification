# Module 12 Report Template

## Overview of the Analysis

The purpose of this analysis is to determine the accuracy with which this model can predict the "health" of a loan, that is to say, whether or not a loan does not have a high risk of defaulting. By looking at the outcomes of a logistic regression model and assessing accuracy, percision, and recall, we can judge the effectiveness of the model and make recommendations for model use or further modelling.

## Results

- Accuracy: 0.99 - 99% of all loans were correctly identified.
- Percision: Healthy Loans: 1.00 - almost all loans labeled "healthy" were actually healthy.
- Percision: Unhealthy Loans: 0.87 - some healthy loans were labeled as high-risk in error.
- Recall: Healthy Loans: 1.00 - almost all healthy loans were correctly labeled.
- Recall: Unhealthy Loans: 0.95 - most unhealthy loans were labeled correctly.

## Summary

This model has very high accuracy in identifying healthy loans, because of this I would recommend it for the company to use. Given the slightly less accurate identification of unhealthy loans, there is still room for improvement and given time, the number of incorrectly identified loans will decrease as more data is able to be used in the fine-tuning of the model.
