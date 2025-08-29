# OLA Cabs Data Analysis Project Report

## Project Overview

This repository presents a comprehensive data analysis project focused on OLA Cabs ride booking data from July 2024. The primary objective was to generate actionable business insights by examining key operational metrics, identifying booking and cancellation patterns, and segmenting performance by vehicle type. The analysis aims to support enhanced business decision-making, operational optimization, and customer satisfaction.

## Data Description

The dataset comprises over 100,000 ride booking records from July 2024. Key variables included:

*   **Booking Information:** Booking ID, date/time, status (success, cancelled by driver/customer, driver not found)
*   **Customer & Driver Details:** Ratings, IDs
*   **Vehicle Type:** Auto, Bike, eBike, Mini, Prime Plus, Prime Sedan, Prime SUV
*   **Ride Metrics:** Distance, ratings, revenue, payment method
*   **Cancellation Reasons:** Segregated for customers and drivers

The raw data was sourced from a spreadsheet, with detailed columns covering booking status, customer and vehicle information, ride details, and cancellation specifics.

## Data Processing & Methodology

Our analytical methodology involved the following steps:

1.  **Data Extraction:** Raw data was imported into SQL, ensuring data integrity and addressing missing or invalid entries.
2.  **Aggregation & Transformation:** Multiple aggregate SQL views were developed to facilitate granular insights, including ride distance per vehicle, cancellation rates, and rating distributions. Examples of these SQL queries are included in the project files.
3.  **KPI Identification:** Focus was placed on impactful business Key Performance Indicators (KPIs), such as booking volume, total booking value, ride success/cancellation rates, payment preferences, and customer/driver sentiment.
4.  **Dashboard Development:** Analyses and visualizations were integrated into a unified dashboard, reflecting both temporal trends and categorical performance breakdowns.

## Results & Key Insights

The analysis yielded several key insights:

*   **Ride Volume & Revenue:** Total bookings exceeded 103,000, with a total booking value of 35 million INR. The success rate was approximately 62%, while the cancellation rate was around 28%. Prime Sedan and Mini categories showed the highest volumes and revenue.
*   **Ride Distance & Customer Engagement:** The average ride distance was approximately 15.53 km. Prime Sedan led in total vehicle-wise distance. A significant portion of rides and revenue was attributed to the top 5 customers.
*   **Cancellations – Trends & Root Causes:** Predominant customer cancellation reasons included "Change of plans" and driver-related issues. Driver cancellations were often due to "Personal & Car related issue" and "Customer related issue." eBikes and Autos had the highest cancellation rates.
*   **Payment Preferences:** UPI was the most popular payment method.
*   **Ratings & Service Quality:** Customer ratings averaged 4.0, with moderate variance in driver ratings.

## SQL Analysis Snapshots

Several SQL views were created to automate and scale insights, including views for successful bookings, ride distance by vehicle, customer and driver cancellations, top customers, payment methods, and ratings.

## Business Recommendations

Based on the analysis, the following recommendations are proposed:

*   **Reduce Cancellations:** Implement targeted interventions for frequent cancellation reasons.
*   **Loyalty Programs:** Engage top customers with reward schemes.
*   **Payment Innovations:** Expand and promote UPI/online payments.
*   **Driver Training:** Focus on driver behavior and support.
*   **Dynamic Fleet Management:** Allocate fleets based on demand periods.

## Conclusion

This analytical dashboard provides OLA's business and operations teams with real-time intelligence on ride patterns, revenue streams, cancellation pain points, and customer/driver experiences. The modular, SQL-driven methodology ensures scalability for ongoing monitoring and supports continuous business improvement.

## Visualizations

Here are some visualizations from the data analysis:

![Overeall](https://github.com/aakashv-X/OLA-Cabs-Data-Analysis/blob/main/Ola%20Cabs/Assets/Overall.png)
![Vehicle Type](https://github.com/aakashv-X/OLA-Cabs-Data-Analysis/blob/main/Ola%20Cabs/Assets/Vehicle%20Type.png)
![Revenue](https://github.com/aakashv-X/OLA-Cabs-Data-Analysis/blob/main/Ola%20Cabs/Assets/Revenue.png)
![Cancellation](https://github.com/aakashv-X/OLA-Cabs-Data-Analysis/blob/main/Ola%20Cabs/Assets/Cancellation.png)
![Ratings](https://github.com/aakashv-X/OLA-Cabs-Data-Analysis/blob/main/Ola%20Cabs/Assets/Ratings.png)


## Appendix

*   Dashboard Visuals – Bookings Trend, Revenue by Payment, Vehicle Performance, Top Customers
*   SQL Script: Complete set of analytical queries/views


