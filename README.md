# Lending Club Case Study


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

- Lending club is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures at lower interest rate loans through a fast online interface.
    <br><br>
- Two types of risks are associated with any company’s decision of lending loan
    <br><br>
	1) If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.
    <br><br>
    2) If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss(credit loss) for the company.
    <br><br>
- The aim of this case study is to understand the driving factors (or driver variables) behind loan default (2nd type of risk), i.e. the variables which are strong indicators of default. Thus, the company can utilize this knowledge for its portfolio and risk assessment. 


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
#### a. Observations 
- 50% of customers apply loans in the range of 5275 to 15000
- Most of the customers have mortgage home or are on rent
- 50% of customers have interest rate between 8.17% to 18.57%

#### b. Risk Analysis  
- Higher the loan amount, more likely the customers are to be defaulted
- At higher interest rate, customers are more likely to be defaulted
- Small_business owners are the highest defaulters
- People with higher income default less
- The rate of defaulters increases from grade A to grade G
- Grade G has highest rate of defaulters, especially when - Annual Income is between 60k to 80k, Loan Amount is between 17500 to 20000 and Interest Rate is above 20%
- The customers with higher sub_grades are ‘risky’ applicants, especially with F5, G5, G3, G2 sub-grades
- The rate of defaulters is more in case of 60 months term
- The rate of defaulters gradually increase from lower debt-to-income ratio to higher debt-to-income ratio
- The top 3 states, having highest chances of getting default customers are NE, NV and SD
- There is more possibilty of defaulters in 1st quater of the year compared to 3rd and 4th quaters
- The customers with employment length 10+ years are having higher rate of defaulters, if we ignore unknown values. But, there is no pattern observed for other length of years
- Across all the income groups, "Loan Amount", "Interest Rate" and "Debt-to-Income Ratio" are higher for the customers who defaulted

> **DRIVING FACTORS: -
           loan_amnt, int_rate, purpose, annual_inc, grade, sub_grade, term, dti, address_state, issue_month**

> **NON-DRIVING FACTORS: -
           home_ownership, verification_status, issue_year, emp_length**

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Pandas - version 1.0.5
- Numpy - version 1.19.5
- Matplotlib - version 3.2.2
- Seaborn - version 0.11.0
- Plotly - version 5.6.0


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->
  

## Contact
Created by [@Divya10Sodha] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
