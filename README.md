# OYO-Hotel-Booking-Analysis
OYO Hotel Booking Analysis – Exploratory Data Analysis (EDA) Project


**Tools Used:**
    Python (Google Colab)
    Libraries: Pandas, NumPy, Matplotlib, Seaborn




**Industry Context:**

The hospitality industry is highly dynamic, where customer behavior and booking trends significantly impact revenue and operational strategies. This project aims to analyze hotel booking data to uncover actionable insights for improving customer experience, optimizing operations, and increasing profitability.

**Project Objective:**

To conduct a detailed exploratory data analysis of hotel booking data to identify key patterns, trends, and anomalies that can drive data-driven decision-making for improved booking management and customer satisfaction.


**About the Data:**


    The dataset consists of hotel booking information, including reservation details, customer demographics, booking lead time, average daily rate (ADR), deposit type, and reservation status.
    Key attributes include hotel type, lead time, arrival date, meal type, and ADR.




**Data Preprocessing Steps:**


    Handling Missing Values:
        Dropped columns with less than 5% null values and imputed others using mean, median, or mode, ensuring no significant data loss.


    Sorting and Removing Duplicates:
        Sorted data by key attributes and removed duplicate records to maintain data integrity and avoid skewed analysis.


    Renaming and Creating New Columns:
        Renamed columns for better readability and created calculated fields such as half lead time to provide additional insights for business needs.


    Data Cleaning and Transformation:
        Dropped irrelevant columns, aggregated data (e.g., average lead time, max/min ADR), and standardized categorical data using .replace() and .apply() functions for consistency.
        Grouped data by hotel type and reservation status, applying aggregation functions to derive insights such as average lead time and reservation patterns.


**Actionable Insights:**


    High Lead Time Patterns:
        Customers with longer lead times were more likely to cancel reservations, indicating the need for flexible booking policies or targeted retention strategies.


    Revenue Contribution by Hotel Type:
        Resort hotels exhibited higher ADR compared to city hotels, suggesting opportunities to market premium packages to drive revenue.




    Seasonality in Bookings:
        Peak booking seasons showed higher cancellations, highlighting the importance of overbooking strategies and efficient resource allocation.


    Impact of Deposit Type:
        Customers choosing "No Deposit" were more likely to cancel their bookings, emphasizing the need to encourage prepayment options.


    Customer Segmentation Insights:
        Families tended to book longer stays compared to solo travelers, providing scope for targeted promotional packages for specific customer segments.


**Key Results:**


    Reduced data anomalies by systematically handling missing values and duplicates, resulting in a clean and comprehensive dataset.
    Derived patterns showing seasonality, lead time behavior, and ADR trends, supporting pricing and operational strategies.
    Delivered interactive visualizations like heatmaps, scatter plots, bar charts, and pair plots to communicate insights effectively.


**Business Impact:**


    Improved decision-making for pricing strategies based on ADR trends and lead times.
    Enhanced operational efficiency by identifying peak booking times and resource allocation needs.
    Increased customer satisfaction through targeted retention strategies and personalized offers.
