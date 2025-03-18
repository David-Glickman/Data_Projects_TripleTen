# SQL Query and Analysis

## Objectives and Goals
The goal of this project was to discover passenger preferences and the impact of external variables on rides for a ride-sharing company in Chicago. The purpose was to test my
knowledge and skills of SQL queries and table joins.

## Overview and Queries 
Four tables were provided to help uncover taxi information: "neighborhoods", "cabs", "trips", and "weather_records".
The following lines will demonstrate each question in the project test, as well as the resulting query that I formulated in SQL editor.

Step 1: Exploratory Data Analysis 

1.Find the number of taxi rides for each taxi company for November 15-16, 2017. Name the resulting field trips_amount and print it along with the company_name field. Sort the 
results by the trips_amount field in descending order:

<img width="691" alt="Screenshot 2025-03-18 at 4 21 51 PM" src="https://github.com/user-attachments/assets/98c6fe90-308f-45d4-bd73-4cd8c777b0f1" />


2.Find the number of rides for every taxi company whose name contains the words "Yellow" or "Blue" for November 1-7, 2017. Name the resulting variable trips_amount. Group the
results by the company_name field:

<img width="693" alt="Screenshot 2025-03-18 at 4 21 18 PM" src="https://github.com/user-attachments/assets/9dddea48-c33d-4db5-8dfa-b4ef50f96c2e" />


3.In November 2017, the most popular taxi companies were Flash Cab and Taxi Affiliation Services. Find the number of rides for these two companies and name the resulting variable
trips_amount. Join the rides for all other companies in the group "Other." Group the data by taxi company names. Name the field with taxi company names company. Sort the result
in descending order by trips_amount:

<img width="710" alt="Screenshot 2025-03-18 at 4 22 21 PM" src="https://github.com/user-attachments/assets/87166bac-7ee2-490c-aa04-e46628cdc046" />


Step 2: Determine if and how the duration of rides from the Loop to O'Hare International Airport changes on rainy Saturdays compared to other days of the week and other weather 
conditions.

1.Retrieve the identifiers of the O'Hare and Loop neighborhoods  from the neighborhoods table:
   
<img width="701" alt="Screenshot 2025-03-18 at 4 22 45 PM" src="https://github.com/user-attachments/assets/e4843cee-9113-4e43-80ee-aa8079f55dde" />


2.For each hour, retrieve the weather condition records from the weather_records table. Using the CASE operator, break all hours into two groups: "Bad" if the description field
contains the words "rain" or "storm," and "Good" for others. Name the resulting field weather_conditions. The final table must include two fields: date and hour (ts) and
weather_conditions:

<img width="695" alt="Screenshot 2025-03-18 at 4 23 10 PM" src="https://github.com/user-attachments/assets/9fa0badd-aca5-4b76-ac1f-d4341a967f87" />


3.Retrieve from the trips table all the rides that started in the Loop (neighborhood_id: 50) and ended at O'Hare (neighborhood_id: 63) on a Saturday. Get the weather conditions for
each ride. Use the method you applied in the previous task. Also retrieve the duration of each ride. Ignore rides for which data on weather conditions is not available:

<img width="679" alt="Screenshot 2025-03-18 at 4 23 29 PM" src="https://github.com/user-attachments/assets/2a23471a-6910-4120-a649-a91035f1d161" />

## Conclusions
Further analysis is required to make meaningful statements about the data; for instance: how do number of rides of competitor companies compare with our company? What are the 
aggregate comaprisons (average) of times of rides during good weather conditions and bad? 

Regardless, I demonstrated proficiency in executing SQL queries- which is what this project tested for.

## Recommendations
Expand the scope of the analysis; come up with metrics to contrast competitors with our company; understand how much inclement weather is impacting both sales and performance,
and come up with dynamic pricing strategies to take advantage of weather conditions.
