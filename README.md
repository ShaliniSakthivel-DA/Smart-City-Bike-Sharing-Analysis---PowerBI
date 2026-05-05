# Smart-City-Bike-Sharing-Analysis---PowerBI

# Objective:

This project analyzes smart bike-sharing station data using Power BI to understand bike availability, station performance, utilization efficiency, and city-wise operational patterns.

# Problem Statement:

• Evaluate the overall utilization of bikes and stations to assess system efficiency
• Identify availability patterns across cities and stations (high, limited, and no availability)
• Analyze trends and detect underperforming areas to improve bike distribution and operational performance

# Attributes:

• Station ID/Name, City (Contract Name), Address, Latitude, Longitude, Date, Year, Month, Total Bikes, Bike Stands, Available Bikes, Empty Stands, Active Stations, Availability Status, Utilization %, Utilization Category

# Data Preparation:

• Performed data cleaning (removed duplicates, handled nulls, fixed address inconsistencies), created calculated columns (imputed address, latitude & longitude, date-only, availability status, utilization category), and developed DAX measures with a measure table along with a calendar table for time-based analysis.

# Data Modelling:

• The model uses a star schema with the Calendar Table as a time dimension, connected to BikeStationDB in a one-to-many relationship (one date → many station records).

# Project Insights

# 1. Descriptive Analysis 

* Most stations have 20–40 stands, while only a few large hubs have up to 70.
* Bike availability is highest in cities like Bruxelles, Lyon, and Toulouse, while some cities have very low or zero availability.
* Many stations face issues: 726 have low availability and 470 are empty, while only 150 perform well.
* Bike fleet increased rapidly from 50 (2022) to 19,450 (2025).
* Some stations have zero bikes, while a few have up to 28 bikes.
* High-demand cities have many low-availability stations.
* Overall utilization rate is low at 34%.
  
# 2. Diagnostic Analysis

* Infrastructure is uneven, with more capacity in some stations than others.
* Bikes are concentrated in major cities, causing shortages in smaller cities.
* Poor redistribution leads to empty stations and oversupply in some areas.
* Rapid growth was not matched with proper planning and distribution.
* High-demand cities face pressure due to more users and limited supply.
* Low utilization shows inefficient use of available resources.

# 3. Predictive Insights 

* Demand will continue to increase in major cities.
* Without better redistribution, empty and overfilled stations will continue.
* System efficiency may improve with better planning and allocation.
* Smaller cities may see growth if distribution is improved.
* Utilization rate can increase with optimized bike movement.
* Data-driven strategies can balance supply and demand better.

<img width="1305" height="727" alt="image" src="https://github.com/user-attachments/assets/e1cbea67-067a-41b2-8a57-3c7fc1d58a65" />

# Conclusion:

The bike-sharing system is expanding rapidly; however, bike distribution and station utilization remain highly uneven. Many stations face shortages while demand is concentrated in major cities. This highlights the need for better resource allocation and redistribution strategies to ensure balanced availability and improved system efficiency.
