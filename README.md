# Credit-Card-Default-Prediction-XGboost-AWS-Sagemaker
In this case study, we will assume that you work as a data
scientist at a bank in Taiwan.
• The bank has collected extensive data about its customers
such as demographics, historical payments record, amount of
bill dollar values.
• Data has been collected between April 2005 to September
2005.
• The data consists of 25 variables.

OUTPUT:
• default.payment.next.month: Default payment (1=yes, 0=no)
INPUTS:
• ID: ID of each client
• LIMIT_BAL: Amount of given credit in NT dollars (includes individual a
nd family/supplementary credit
• SEX: Gender(1=male, 2=female)
• EDUCATION: (1=graduate school, 2=university, 3=high school, 4=other
s, 5=unknown, 6=unknown)
• MARRIAGE: Marital status (1=married, 2=single, 3=others)
• AGE: Age in years
• PAY_0: Repayment status in September, 2005 (-
1=pay duly, 1=payment delay for one month, 2=payment delay for two
months, ... 8=payment delay for eight months, 9=payment delay for n
ine months and above)
• PAY_2: Repayment status in August, 2005 (scale same as above)
• PAY_3: Repayment status in July, 2005 (scale same as above)
• PAY_4: Repayment status in June, 2005 (scale same as above)
• PAY_5: Repayment status in May, 2005 (scale same as above)
• PAY_6: Repayment status in April, 2005 (scale same as above)
• INPUTS (CONTINUED):
• BILL_AMT1: Amount of bill statement in September, 2005 (NT dollar)
• BILL_AMT2: Amount of bill statement in August, 2005 (NT dollar)
• BILL_AMT3: Amount of bill statement in July, 2005 (NT dollar)
• BILL_AMT4: Amount of bill statement in June, 2005 (NT dollar)
• BILL_AMT5: Amount of bill statement in May, 2005 (NT dollar)
• BILL_AMT6: Amount of bill statement in April, 2005 (NT dollar)
• PAY_AMT1: Amount of previous payment in September, 2005 (NT do
llar)
• PAY_AMT2: Amount of previous payment in August, 2005 (NT dollar)
• PAY_AMT3: Amount of previous payment in July, 2005 (NT dollar)
• PAY_AMT4: Amount of previous payment in June, 2005 (NT dollar)
• PAY_AMT5: Amount of previous payment in May, 2005 (NT dollar)
• PAY_AMT6: Amount of previous payment in April, 2005 (NT dollar)
XGBOOST: INTRODUCTION
• XGBoost or Extreme gradient boosting is the
algorithm of choice for many data scientists and
could be used for regression and classification
tasks.
• XGBoost is a supervised learning algorithm and
implements gradient boosted trees algorithm.
• The algorithm work by combining an ensemble of
predictions from several weak models.
• It is robust to many data distributions and
relationships and offers many hyperparameters to
tune model performance.
• Xgboost offers increased speed and enhanced
memory utilization.
