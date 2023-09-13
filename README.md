# Cohort-Analysis

## Introduction

This project focuses on building time-based Cohort Analysis and evaluating user engagement from their first transaction. Customers will be divided into acquisition cohorts depending on the month of their first purchase. The cohort index would then be assigned to each of the customer’s purchases, which will represent the number of months since the first transaction.
The input data is the KPMG transaction data file (HomeTest 1 - KPMG Data) as follows:

| Column name | Data type |
| ----------- | --------- |
| transaction_id | integer |
| product_id | integer |
| customer_id | integer |
| transaction_date | datetime |
| online_order | boolean |
| order_status | string |
| brand | string |
| product_line | string |
| product_class | string |
| product_size | string |
| list_price | float |
| standard_cost | float |
| product_first_sold_date | integer |

## Handling process

1. Create dataframe and clean data.
2. Determine each customer's first month of trading.
3. Determine what month each transaction is in since that customer's first transaction.
4. Count the number of customers making transactions in each month of the year and the number of months.
5. Calculate x month's retention rate = x number of monthly buyers / 1st month number of buyers * 100
6. Creating the cohort chart.
7. Evaluate user engagement from their first transaction.

## Result

*Although this result is different from most other people's results and different from the answer I received, after a period of thinking, I still decided to keep this result. The reason is that I am not convinced by their way of calculating the number of months of participation for each customer. Or maybe from the perspective of a researcher who always wants everything to be calculated in detail, and has absolutely no background in economics like me, so my understanding of the problem is not correct. I look forward to receiving comments that will help me shed more light on this issue.*

- Visualize customer retention rates

![Screenshot 2023-09-13 173321](https://github.com/dieppnguyen/Cohort-Analysis/assets/142650906/e4241b2e-72fe-4f81-a971-919a2c3b86a7)


- Some customer retention assessments derived from visualization

![Screenshot 2023-09-13 173437](https://github.com/dieppnguyen/Cohort-Analysis/assets/142650906/cb11a417-f407-47a8-9b6b-e45b5f0b4aad)
