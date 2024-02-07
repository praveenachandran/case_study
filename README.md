# Project Name
> Lending Club case Study


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The company wants to identify factors influencing loan default to minimize credit loss.
- The goal is to develop an understanding of how consumer attributes and loan attributes influence the tendency of default.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
### Observations from the Lending Club Case Study:

- Null Values: The dataset had missing values, which were dropped to ensure data quality.

- Outlier Treatment: Outliers in the 'annual_inc' (annual income) column were identified using box plots and removed based on the 95th percentile threshold.

- Univariate Analysis:

    Loan Status Distribution: About 85% of borrowers paid their loans in full, 14% defaulted, and 5% were in the process of repaying.
    State-wise Distribution: California had the highest number of loan applications.
    Term Distribution: The majority of loan applications had a term of 36 months.
    Loan Purpose Distribution: Debt consolidation was the most common purpose for taking a loan.

- Bivariate Analysis:

    Grade vs. Loan Status: Grades B, A, C, and D contributed the most to "Charged Off" loans.
    Loan Amount vs. Loan Status: Charged Off loans had higher loan amounts than Fully Paid ones.
    Annual Income vs. Loan Status: Charged Off loans had lower annual incomes than Fully Paid ones.
    Term vs. Loan Status: The proportion of defaulted loans was higher for 60-month terms compared to 36-month terms.
    Home Ownership vs. Loan Status: Rent and Mortgage categories had the highest number of Charge Offs.
    Verification Status vs. Loan Status: Most loans were given without verifying applicants' income.
    Employment Length vs. Loan Amount: Borrowers with 10+ years of employment had the highest loan amounts.
    Purpose vs. Loan Status: Loans for debt consolidation were more likely to be charged off (defaulted).
  
- Business Driven Metrics:

    Most borrowers repay their debts on time, and their debt levels are manageable in relation to their income.

- Data Driven Metrics:

    Descriptive Statistics: Summary statistics were provided for numerical columns.
    Frequency Distribution: Counts were shown for categorical columns ('grade', 'sub_grade', 'home_ownership', 'verification_status').
    Derived Ratios Distribution: Debt-to-Income Ratio distribution was visualized using histograms.
    
- Segmentation:

    Loan-to-Income Ratio was segmented into Low, Medium, and High risk categories based on the loan amount relative to annual income.


## Technologies Used
- Python - version 3.11.4
- Matplotlib - version 3.8.2
- Seaborn - version 0.13.2

## Acknowledgements
- Exploratory Data Analysis (EDA) on the learning platform

## Contact
Created by [praveenachandran@gmail.com] [kinshuksoperna@gmail.com] - feel free to contact us!

