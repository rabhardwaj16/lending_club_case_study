# lending_club_case_study
> Lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. We want to understand the **driving factors** which are strong indicators of default.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
> Lending Club is a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

- If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company


> Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

- Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

- Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

- Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

> Here we want to understand the **driving factors** which are strong indicators of default.

> We have historical data of the loan provided by the company in the period period 2007 to 2011.


## Conclusions
- more than 21600 loans were issued in `2011` hence most of the Charged Off cases were seen in the same Year.

- 38% of the customers who went Charged Off were `not verified`. Means if the customers are `not verified` they could get defaulted.

- 49.22% of the total customers who went Charged Off have stated the purpose for the loan as `Debt Consolidation`. Hence, the customers who states purpose as `Debt Consolidation` are likely to get defaulted.

- annual income of maximum people living on `Rent` and `Mortgage` is less than `1 Lakh`.

- 85.45% of the total Charged Off customers have annual income less than `1 Lakh`. Hence, the customers having annual income is less than `1 Lakh` are most likely to get defaulted.

- 91.81% of the total customers who went Charged Off were living on `Rent` and `Mortgage`. This means the customers living on `Rent` or having `Mortgage` are most likely to get defaulted.

- 48.36% of the customers who went Charged Off were from 5 States i.e., `CA`, `FL`, `NY`, `TX` and `NJ`. Out of which around 20% were from `CA`. People applying for loan from State CA are most likely to be defaulted.


## Technologies Used
- Pandas - version 1.5.1
- Numpy - version 1.23.4
- Matplotlib - version 3.6.0
- Seaborn - version 0.12.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@rabhardwaj16] - feel free to contact me!
