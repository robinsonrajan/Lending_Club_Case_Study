# Lending Club Case Study
>The objective of this case study is to perform exploratory data analysis (EDA) to identify patterns and understand how consumer attributes and loan attributes influence the tendency of loan default. The aim is to identify the variables that can help predict whether an applicant is likely to default or not. This information can be used by the consumer finance company to make loan approval decisions and mitigate the risk of financial loss due to defaults.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Business Objective  
    The task at hand is to analyze data on past loan applicants to identify patterns that can help a consumer finance company make loan approval decisions based on an applicant's likelihood to repay the loan or default. The company faces two risks: losing business if a likely-to-repay applicant is denied a loan and suffering financial loss if a likely-to-default applicant is approved. The analysis may result in actions such as denying loans, reducing loan amounts, or lending to risky applicants at higher interest rates. The company can also use the analysis to identify potential customers who are likely to default and target them with marketing campaigns to increase the likelihood of repayment.
- What is the background of your project?  
    The background of the project is that it involves a consumer finance company specializing in lending various types of loans to urban customers. The company needs to make loan approval decisions based on the applicant's profile and faces two risks: losing business by denying a loan to a likely-to-repay applicant or suffering financial loss by approving a loan to a likely-to-default applicant. The company wants to use EDA to identify the variables that can help predict whether an applicant is likely to default or not.
- What is the business probem that your project is trying to solve?  
    The business problem that the project is trying to solve is the identification of risky loan applicants who are likely to default. Defaulting borrowers cause the largest amount of financial loss (credit loss) to the lenders, and identifying these applicants through EDA can help reduce the amount of credit loss by cutting down on risky loans. The project aims to understand the driving factors behind loan default and identify the variables that are strong indicators of default, thereby helping the company to make informed decisions about loan approval.
- What is the dataset that is being used?  
    loan.csv is the dataset being used for the project. The dataset contains 39717 observations and 111 variables. The dataset contains information on loan applicants and their loan details.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Borrowers have mostly taken loans for 36 months however the charged off percentage is higher for 60 months loans.
- Higher loan amount and interest rate are associated with higher charged off percentage.
- Borrowers with lower annual income are more likely to default on their loans. Annual income below 90K is associated with higher charged off percentage.
- Higher debt to income ratio, public record of bankruptcy and revolving utilization are associated with higher charged off percentage.
- The loans borrowed for small business, renewable energy and educational purposes have higher charged off percentage indicating that these loans are riskier. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.10.10
- Numpy - version 1.24.2
- Pandas - version 1.5.3
- Matplotlib - version 3.7.1
- Seaborn - version 0.12.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This case study is part of the course Executive PG Programme in Machine Learning and Artificial Intelligence offered by UpGrad.
- The dataset is provided by UpGrad.


## Contact
Created by @robinsonrajan and @mikenextml - feel free to contact us!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->