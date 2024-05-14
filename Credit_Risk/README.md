## Purpose of the Study

The purpse of this Analysis by using Logisitc Regression and Predict "Loan_Status" involves understanding and indentifying the factors that influence where a loan will be repaid or defaulted. this prediction is crucial for the following reasons:

- Risk Management:
Assess Risk: by predicting the likelihood of a loan default, finential institutions can better manage the risk associated with lending. it allows them to take preemitive measures to miligage losses

- Customize Loan Offers: based on the risk profile of borrowers, lenders can tailor loan terms, including interest rates and repayment schedules to balance risk and reward

- Credit Scoring: Logistic Regression helps in analyzing the borrower's finential background and other demographic factors to assign a credit score. and the score influence the decision to grant a loan.

## Result Of The Study

                    Precision   Recall  F1-Score    Support

0(healthyloan)              1.00        0.99     1.00       18765

1 (High-Risk-loan)          0.84        0.94     0.89       619

Macro Avg                    0.92        0.97       0.94     19384      
Weight Avg                   0.99        0.99       0.99     19384

Test_Score is 99.25%

## Summary

The model perfoms exceptionally well in identifying healthy loans with nearly perfect precision and recall. in terms of high-risk-loans, while recall is high (meaning it catches most the high rik loans). percesion is somwhat low, which suggests that there are some false positives-healthy loans misclassified as high-risk. This could potentially lead to unnecessary checks or denial of loans which are actually safe, thus potentially impacting customer satisfaction negatively.

Given these results the model is highly effective and reliable, especically for it ability to flag high-risk loans, which is crucial to minimize the risk defaults.


