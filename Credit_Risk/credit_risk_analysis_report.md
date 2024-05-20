# Credit Risk Assessment

## Overview of the Analysis

The purpose of this analysis is to evaluate the performance of a logistic regression model in predicting the creditworthiness of borrowers. Using a dataset of historical lending activity from a peer-to-peer lending services company, I aim to build a model that can accurately identify high-risk loans and healthy loans. This analysis is crucial for the company to make informed lending decisions and mitigate financial risks.

## Results

* Accuracy Score: 0.99
* Precision Score:
    * Healthy Loan: 1.00
    * High-Risk Loan: 0.85
* Recall Score:
    * Healthy Loan: 0.99
    * High-Risk Loan: 0.91

## Summary

The logistic regression model demonstrated outstanding performance in predicting healthy loans, with a precision score of 1.00 and a recall score of 0.99. This means that nearly all loans classified as healthy by the model were indeed healthy, and 99% of actual healthy loans were correctly identified.

For high-risk loans, the model achieved a precision score of 0.85 and a recall score of 0.91. While these scores are slightly lower than those for healthy loans, they are still quite strong, indicating that the model is effective in identifying high-risk loans.

Given the high overall accuracy (0.99) and the strong performance metrics, I recommend using this model for predicting loan statuses. The model's ability to accurately identify both healthy and high-risk loans makes it a valuable tool for the company in managing credit risk.
