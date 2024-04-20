
# Bank Loan Analysis
This project aims to demonstrate some KPIs regarding Bank Loans and visualize them with proper visual charts.

The report consists of 3 pages:

  **1**: Summary

  **2**: Overview

  **3**: Details


## Table of Contents
- Problem Statement
- Data Source
- Tools
- Skills/ Concepts demonstrated
- Data Transformation
- Data Modeling
- Visualization
- Analysis

### Problem Statement

1- What are the KPIs and their values?

- Total Loan Application

- Total Funded Amount & Total Amount Received

- Avg.Interest Rate and Average Debt-to-Income Ratio (DTI)

2- To identify seasonability and long-term trends in lending activities

3- To allow the client to understand the distribution of loans across various term lengths.

4- How lending metrics are distributed among borrowers with different employment lengths, helping us assess the impact of employment history on loan applications

5- Will provide a visual breakdown of loan metrics based on the stated purposes of loans, aiding in the understanding of the primary reasons borrowers seek financing.

6- For a hierarchical view of how home ownership impacts loan applications and disbursements.

7- Good vs Bad Loan Comparison

### Data Source
The primary dataset used for this analysis is the "financial_loan.csv" file, containing detailed information.

### Tools

- PowerBI (Creating reports)

### Skills/ Concepts demonstrated

- DAX (Calculate,SUM,Average,TOTALMTD,Divide,DATESMTD,Selectedvalue)
- Page Navigation
- Filters
- Modeling
- Power Query
- Date Table
- Formatting visuals
- Creating Group 
- Concatenate measure with text (for titles)

### Data Transformation
Data cleaning and transformation were made in Power Query. Date format of the date columns was changed to "dd-mm-yyyy".

In the report view, 2 groups were created based on loan status Good Loan & Bad Loan. Good Loan means loan status is "Current" & "Fully Paid", and Bad Loan means loan status is "Charged Off".

### Data Modeling
![Model View](https://github.com/burcinalim/My-Data-Analysis-Portfolio/blob/main/01-Bank%20Loan%20Analysis%20Project/Screenshots/Model%20View.png?raw=true)


### Visualization

 1- Summary Page:
 ![Summary Page](https://github.com/burcinalim/My-Data-Analysis-Portfolio/blob/main/01-Bank%20Loan%20Analysis%20Project/Screenshots/1-Summary%20Page.png?raw=true)

 2- Overview Page:
![Overview Page](https://github.com/burcinalim/My-Data-Analysis-Portfolio/blob/main/01-Bank%20Loan%20Analysis%20Project/Screenshots/2-Overview%20Page.png?raw=true)

 3- Details Page:
![Details Page](https://github.com/burcinalim/My-Data-Analysis-Portfolio/blob/main/01-Bank%20Loan%20Analysis%20Project/Screenshots/3-Details%20Page.png?raw=true)

### Analysis
- In the overall Total 39K applications were made by customers
- Average Interest Rate was 12.05%
- Average debt-to-income ratio was 13.33%
- Applications count for loans we consider Good Loans, which is the sum of "Current" & "Full Paid" values according to the loan status column, more than Bad Loans. 
- The most loan was given for debt consolidation, and after that for Credit Card.
- Most of the debtors have 10+ years of employee length which gives us confidence that they repay their debt.
- The most debt was borrowed in December.
- 62.66% of loans were given for 36 months term.
## Color Reference

The details of the color palettes used for this dashboard are in the "Color Palettes" file.

