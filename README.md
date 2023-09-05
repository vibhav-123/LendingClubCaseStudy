# Lending Club Case Study
> This is a case study to understand the various factors that contribute to defaulting of a loan based on the loan dataset provided by UpGrad.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
This is an attempt to do Exploratory Data Analysis(EDA) on the customer loan dataset to derive insights related to what factors contribute to loan defaulting by consumers.

This analysis would help the bank to make better decisions in giving loans to customers.

The following steps are taken while doing the analysis:
1. Data cleaning:
    - Dropping columns with more than 75% missing values.
    - Modified column data types.
2. Univariate Analysis
3. Segmented Analysis
4. Bivariate Analysis
5. Deriving new columns like principal amount.

## Conclusions
1. Customers with higher loan time period have a higher tendency to default their loans.
2. Customers with high principal amount are more likely to default their loans.
3. Customers having an annual income less than ₹75000 are more likely to default their loans.
4. Customers living on rent or mortgage have a 50% rate of loan defaulting among the total defaulters.

## Technologies Used
- Python v3.0
- Pandas v2.1.0
- Numpy v1.25
- Matplotlib v3.7
