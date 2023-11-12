# Loan-Repayment-Prediction
## Context

LendingClub is an American peer-to-peer lending company headquartered in San Francisco, California. It was the first peer-to-peer lending company to register its offerings with the U.S. Securities and Exchange Commission and offer secondary market trading of loans. 

LendingClub is the world's largest peer-to-peer lending platform.

**Main goal:** Having historical data on loans issued with information on whether the borrower defaulted (write-offs), we need to build a model that can predict whether the borrower will repay his loan or not.

Thus, in the future, when we receive a new potential client, we will be able to assess whether they will be able to repay the loan.

## Selected Model
After numerous training and algorithm changes, I concluded that the best model for this problem would be artificial neural network with pre-scaled data using the StandardScaler**.

## Results
The maximum achieved accuracy of the model is 89%. But do not forget that the set used for training was not balanced from the beginning.

## Requirements
1. numpy==1.23.5
2. pandas==1.5.3
3. matplotlib==3.6.3
4. seaborn==0.12.2
5. scikit-learn==1.2.1
6. tensorflow==2.12.0