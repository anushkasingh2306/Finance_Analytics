# Finance_Analytics of AtliQ Hardware
Welcome to the AtliQ Hardware Data Analytics Project Repository. In this project I have used MySQL to generate insightful reports.

## Problem Statement
AtliQ Hardware is a company that sells computer hardwares to clients which has several branches throughout India. AtliQ Hardware emerged as the first indigeneous manufacturers of computer peripherals in India. As a result their sales and revenue increased every year. As the size of excel files continues to grow, it is encountering performance issues, causing them to become unresponsive and stopped working. To adress this challenge AtliQ Harware hired aa team of data analysts who will use MySQL as their database management system and to extract valuable insights from the data. These insights will empower our company to make more informed and strategic decisions, ultimately optimizing our operations and performance.

## Business Terminology
- Fiscal Year
- Gross Price
- Gross Price Total

## Insights

### Product Sales Report


<img width="437" alt="1" src="https://github.com/anushkasingh2306/Finance_Analytics/assets/123302995/ac4331f8-3313-417a-89eb-8bd45e745ba5">

- I created two user-defined functions get_fiscal_year and get_fiscal_year_quarter.
- I used JOIN to get the report.


<img width="403" alt="Sql" src="https://github.com/anushkasingh2306/Finance_Analytics/assets/123302995/b4664184-ecd0-4656-bf77-4fec464308fa">


- I generated a report for product sales for Croma India customer for fiscal_year = 2021
- This report will help in tracking individual product sales and help in analysing products.
  
  <img width="578" alt="r" src="https://github.com/anushkasingh2306/Finance_Analytics/assets/123302995/34628dab-d49c-4336-a155-bddea3e31b29">
[croma__2021_all_trans.csv](https://github.com/anushkasingh2306/Finance_Analytics/files/12880376/croma__2021_all_trans.csv)

### Gross Monthly Total Sales Report



<img width="457" alt="gross" src="https://github.com/anushkasingh2306/Finance_Analytics/assets/123302995/619b6b53-7205-4fe0-8839-70d81d9cfac9">

- Performed aggregate function (SUM) to calculaye gross_price_total
- Joined two tables fact_sales_monthly and fact_gross_price.

  
<img width="386" alt="S2" src="https://github.com/anushkasingh2306/Finance_Analytics/assets/123302995/79a26e75-d7a1-4131-85f0-e10bd36d4f5c">

- I generated a report for gross_price_total.

<img width="150" alt="R2" src="https://github.com/anushkasingh2306/Finance_Analytics/assets/123302995/b4b45f76-33ff-4545-a49f-5b5790a6e917">
[monthly_sales.csv](https://github.com/anushkasingh2306/Finance_Analytics/files/12880396/monthly_sales.csv)

### Yearly Sales Report

<img width="400" alt="Q3" src="https://github.com/anushkasingh2306/Finance_Analytics/assets/123302995/286ec687-fe06-4f7a-bf0e-2474e75d9706">

- Retrieved fiscal_year using user-defined function get_fiscal_year.
- Calculated yearly_sales using aggregate function(SUM).
- Joined two tables fact_sales_monthly and fact_gross_price.
 
<img width="338" alt="S3" src="https://github.com/anushkasingh2306/Finance_Analytics/assets/123302995/c6581251-830b-4e57-91a1-1d49356d3e4d">

- I Generated a report for Croma India.
- In the fiscal year 2022 Croma India has the highest sales.

<img width="213" alt="R3" src="https://github.com/anushkasingh2306/Finance_Analytics/assets/123302995/75fc9a12-e8bb-4f10-8576-880b958413d5">
 [yearly_sales.csv](https://github.com/anushkasingh2306/Finance_Analytics/files/12880402/yearly_sales.csv)












