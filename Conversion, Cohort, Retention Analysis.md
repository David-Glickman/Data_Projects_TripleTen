# Conversion, Cohort, Rentention Analysis

## Objectives and Goals
The objective of this project was to analyze customer conversion rates, establish customer cohorts based on date of first purchase, and identify customer retention over time for 
an e-commerce store. The goal was designed to test my understanding of business metrics as well as exercise my spreasheet skills.

## Overview
Initial table was drawn from raw user data of an e-commerce company's transaction logs. A pivot table was created to show user conversion rates from each stage, pageviews all the way 
to purchases. 

To establish cohorts, I first created a new table out of the raw data called purchase activity, defined only by those entries where a purhcase event took place. I filtered first
purchase dates, and created a new column for them. Cohort age was then established in this table by subtracting first month of purchase activity by current month of purchase activity. 
A pivot table was then generated, ordering unique count of User IDs by first purchase and cohort age. Finally, I refined this table into a new retention rates pivot table, 
demonstrating the % of customers within a cohort still purchasing in each successive month. 
<img width="706" alt="Screenshot 2025-03-07 at 2 01 49 PM" src="https://github.com/user-attachments/assets/52e7fc1a-d08e-4f10-8667-113d247afd1d" /> 
<img width="1082" alt="Screenshot 2025-03-07 at 2 02 20 PM" src="https://github.com/user-attachments/assets/b6006b4e-9cbe-43d5-80c8-125df50e7872" />
<img width="721" alt="Screenshot 2025-03-07 at 2 02 58 PM" src="https://github.com/user-attachments/assets/2a821891-1bca-416a-a552-8efb83dacf93" />
<img width="592" alt="Screenshot 2025-03-07 at 2 03 43 PM" src="https://github.com/user-attachments/assets/86519dd3-812e-48b2-9403-d2a969f2603a" />

## Conclusion
Conversion rates are adequate; 10% of users who land on the site make a purchase; 36% of those who fill their shopping carts make a purchase. The first cohort from 2020-09 had the 
best first month customer retention rate; most cohorts continue to lose users with each successive cohort, untill a jump back to 7% retention for the cohort of 2021-01. The 
raw_user_activity dataset ends in February, 2021, so it becomes increasingly difficult to draw conclusions about later trends. The first three cohorts gradually dwindle off into 
the low single digits of retention, with an anomaly of cohort one coming back to life in February of 2021. Customer retention is quite poor across the board.

## Recommendations
Increase marketing efforts, loyalty rewards for customers to increase retention across the board. Perform further analysis to identify which specific marketing campaign occurred
when the first cohort made its purchase; further analysis to determine why the first cohort gained retention in its fourth month. 

## [Link to project](https://docs.google.com/spreadsheets/d/1Qu4naTMAI0QKuOTFdlzkE84Xm2oNP4h7EChGCIkoL1Y/edit?usp=sharing) 
