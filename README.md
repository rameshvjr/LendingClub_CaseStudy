
# A case study on "Lending Club"

We are workging for a consumer finance company which specialises in lending various types of loans to urban customers. 
When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. 


## Table of Contents

* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information

- There are two types of risks are associated with the bank’s decision:
1: If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
2: If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

- company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment. 

- The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

- Company can take any one of the decision on loan application - either grant or reject. The dataset we are using is having only granted / accepted loans in the span of 2007 to 2011.

- Using the concept of EDA to perform the risk analysis and propose the potential risk indicators.


## Conclusions

As per the given source loan data, following are few factors / risk indicators which conveys potential loan default scenarios.

- High Interest Rate (beyond ~13%)
- High Annual Income (35+ k range)
- Long Term (60 months)
- Loan purpose to consolidate debts and to replay credit card bills
- High experienced loan applicants who are taking high amount (better to avoid to mitigate risk)

So, in summary, Annual Income, Home Ownership, Purpose of Loan, Loan Amount, Interest Rate, and Loan Term are critical factors to be considered by Underwriters who perform Risk analysis and decide whether to reject the loan or grant the loan.


## Technologies Used
- Python 3.0
- Jupyter Notebook
- Libraries used in this case study:
    - numpy: version 1.21.5
    - pandas: version 1.4.2
    - matplotlib: version 3.5.1
    - seaborn: version 0.11.2

## Acknowledgements
Give credit here.
- This project was inspired by efforts of some of our UpGrad Alumini students.
- References: 
    - https://stackoverflow.com/
    - https://pynative.com/

## Contact
Created by [@rameshvjr] - feel free to contact me!