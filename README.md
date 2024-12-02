# lab-big-query

## 🚖 NYC Taxi Public Dataset - SQL Exercises

### 📋 Description

This repository contains SQL queries designed to analyze the NYC Taxi Yellow Trips dataset from Google BigQuery. The exercises aim to demonstrate proficiency in SQL querying, data manipulation, and analysis using the publicly available taxi trip data. The dataset includes information on taxi rides, including trip distances, fares, pickup/dropoff locations, passenger counts, and payment types.

This project is part of the Ironhack Data Analytics Bootcamp curriculum, specifically focusing on using Google BigQuery to run SQL queries for data analysis.

### 🔑 Prerequisites

- **Google BigQuery**: A platform for running SQL queries on large datasets.
- **NYC Taxi Yellow Trips dataset**: Public dataset available on Google BigQuery.

### 🔄 Exercises

The following exercises were completed to analyze different aspects of the NYC Taxi dataset:

1. **Count the number of trips in January 2023**
   - SQL query to calculate the total number of taxi trips that occurred in January 2023.
   
2. **Calculate the total revenue generated by taxi trips in 2023**
   - SQL query to sum up the total revenue generated from all taxi rides in 2023.

3. **Find the most popular pickup location**
   - SQL query to determine which pickup location had the most taxi trips.

4. **Analyze the number of trips per hour of the day**
   - SQL query to break down taxi trips by the hour of the day to see when the highest number of trips occurred.

5. **Calculate the average trip distance**
   - SQL query to calculate the average distance of all taxi trips in the dataset.

6. **Find the longest trip by distance**
   - SQL query to identify the longest trip in terms of distance traveled.

7. **Calculate the total number of passengers by payment type**
   - SQL query to calculate the total number of passengers for each payment method (e.g., cash, credit card).

8. **Find the most common drop-off location for trips paid by credit card**
   - SQL query to determine the most common drop-off location for trips that were paid with a credit card.

9. **Calculate the total number of trips that had more than 4 passengers**
   - SQL query to count the number of trips where the number of passengers was greater than 4.

10. **Subquery - Find the average fare for trips longer than the average trip distance**
    - SQL query using a subquery to find the average fare for trips whose distance was longer than the overall average trip distance.

### 🧑‍🏫 Instructions

1. Clone this repository.
2. Open your Google BigQuery console and load the NYC Taxi Yellow Trips dataset.
3. Run each SQL query provided in the `queries` folder or execute them directly on your Google BigQuery console.
4. Verify the results based on the expected outcomes.

### 📂 Directory Structure

- **queries**: Folder containing all SQL queries for each exercise.
- **README.md**: This file, describing the project and exercises.

### 🚀 Getting Started

1. Open your Google BigQuery account and access the NYC Taxi Yellow Trips dataset.
2. Run the SQL queries from the `queries` folder or directly input them in the Google BigQuery query editor.
3. Make sure to check the results of each exercise, and feel free to adapt the queries to explore the dataset further.

### ✨ Future Enhancements

- Add additional data analyses or create visualizations of the data using tools like Tableau, Power BI, or Matplotlib.
- Extend the exercises to include machine learning models to predict trip characteristics based on historical data.
