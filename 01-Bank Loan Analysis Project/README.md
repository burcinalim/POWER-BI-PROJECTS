
# Bank Loan Analysis

## Table of Contents
- Problem Statement
- Data Source
- Tools
- Steps Followed to Create Report

### Problem Statement

This dashboard helps the bank monitor the health of their loan customer portfolios, identify underperforming loans, and optimize loan terms and pricing. The bank also can use data to evaluate the creditworthiness of borrowers, predict default probabilities, and determine interest rates and lending terms. Analyzing loan data provides insights into customer behavior, preferences, and needs. The bank can use these insights to tailor loan products and marketing strategies to specific customer segments.
### Data Source
The primary dataset used for this analysis is the "financial_loan.csv" file, containing detailed information.

### Tools
-PostgreSQL (Data analysis)

-PowerBI (Creating reports)

### Steps Followed to Create Report

- Step 1 : Load data into Power BI Desktop, the dataset is a CSV file.
- Step 2 : Open the power query editor & in the view tab under the Data Preview section, and check the "column distribution", "column quality" & "column profile" &" date format" options.
- Step 3 : In the table view, the Date Table was created based on issue_date within the main table.
- Step 4 : Necessary measures were created under the All Measures Table to represent the visuals mentioned below. The data was grouped into Good Loans (current & fully paid) and Bad Loans (charged off) by using the loan status column.

  (a) Total Loan Applications

  (b) Total Funded Amount
  
  (c) Total Amount Received
  
  (d) Avg. Interest Rate
  
  (e) Avg. DTI
  
  (f) Good Loans Percentage (and details)

  (g) Bad Loans Percentage (and details)
  
  (h) Loan Status Summary
  
- Step 5 : Visual filters (Slicers) were added for three fields named "Grade", "Purpose", and "State" into the Summary Page.
- Step 6 : The Summary Page was designed by adding some shapes and a page navigator. Also, the coolors website was used for the color palette.
- Step 7 : After creating the Summary Page, Overview & Details pages were designed based on the Summary Page.
- Step 8: The below visuals were added to the Overview page. Also, the Fields parameter was created using the Modeling Tab. This was used to filter the below visuals according to Total Loan Application, Total Funded Amount, and Total Amount Received.

  (a) Two bar charts to present data by purpose and employee length measures.

  (b) An area chart to present data by month values.

  (c) A treemap to present data by home ownership values.

  (d) A donut chart to present data by term values.

- Step 9 : A table was added to the Details page to demonstrate loan owner details.

## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

## Color Reference

The details of the color palettes used for this dashboard is the "Color Palettes" file.


## Authors

- [@burcinalim](https://github.com/burcinalim)

