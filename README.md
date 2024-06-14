# credit-risk-classification analysis

Overview

The purpose of this analysis is to evaluate the performance of a logistic regression model in predicting loan statuses, specifically distinguishing between healthy loans (label 0) and high-risk loans (label 1). This evaluation helps determine the model's effectiveness and reliability in identifying potential high-risk loans, thereby aiding the company in managing its loan portfolio more effectively and mitigating financial risk.




Precision:


Healthy Loan (0): 1.00 (The model perfectly predicts healthy loans with no false positives.)
High-Risk Loan (1): 0.85 (85% of the predicted high-risk loans are indeed high-risk.)
Recall:
Healthy Loan (0): 0.99 (99% of the actual healthy loans are correctly identified.)
High-Risk Loan (1): 0.91 (91% of actual high-risk loans are correctly identified.)

Summary of Results


The logistic regression model demonstrates excellent performance in predicting loan statuses, with an overall accuracy of 99%. The precision and recall for healthy loans (label 0) are nearly perfect, indicating that the model is extremely reliable in identifying healthy loans. For high-risk loans (label 1), the precision is 0.85 and recall is 0.91, which are strong but slightly lower than for healthy loans. This means that while the model is good at identifying high-risk loans, there are some false positives and a few high-risk loans that are not identified.

