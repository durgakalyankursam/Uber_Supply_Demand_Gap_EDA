# Project Summary -
This project performs an exploratory data analysis of Uber request data to understand the major reasons why customer ride requests are not successfully completed and to identify the operational periods where the service experiences the greatest imbalance between demand and available drivers. The dataset contains 6,745 ride requests made between 11 July 2016 and 15 July 2016, with information on request ID, pickup point, driver ID, request time, drop time and request status.

The analysis starts by checking the structure, data types, duplicates and missing values. Missing Driver ID values are expected for requests that did not result in an assigned driver, while missing Drop timestamps occur for trips that were cancelled or had no cars available. Request timestamps are converted into datetime format so that hour, day and weekday patterns can be studied. Trip duration is calculated for completed rides, and additional categorical indicators are created to distinguish completed and unfulfilled requests.

# Problem Statement
Analyze Uber ride-request data to identify patterns in request demand, trip completion, customer cancellations, and driver unavailability, with special focus on time of day and pickup location. The objective is to determine the major causes of unsuccessful requests and recommend operational actions that can improve the ride completion rate.

# Define Your Business Objective?
The business objective is to increase the percentage of ride requests that are successfully completed by identifying when and where demand exceeds available driver supply, while separately understanding customer cancellations. The analysis should help Uber improve driver allocation, reduce “No Cars Available” requests, reduce avoidable cancellations, and improve the customer experience during peak demand periods.
