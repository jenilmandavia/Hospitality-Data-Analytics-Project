# Hospitality-Data-Analytics-Project
This project showcases hotel industry domain analytics and provides some remarkable insights from the analysis. 

##  Project Overview

This project aims to analyze and uncover key patterns in hotel booking behavior, revenue generation, occupancy performance, and guest trends across different hotel types, cities, and booking platforms.

---

##  Business Objectives

- Identify **booking trends** across weekdays vs weekends.
- Analyze **room occupancy and capacity** utilization by category and city.
- Understand the impact of **booking platforms** on cancellations and revenue.
- Explore **revenue leakage** due to cancellations and no-shows.
- Measure **customer satisfaction** by correlating ratings with booking behavior.

---

##  Data Summary

The dataset includes over 50MB of booking, room, hotel, and calendar data with the following fact and dimension tables:

- `fact_bookings`: Individual booking transactions with guest count, status, platform, and revenue.
- `fact_aggregated_bookings`: Daily capacity and successful booking counts by hotel and room type.
- `dim_hotels`: Hotel-level info such as city and category (Luxury, Business).
- `dim_rooms`: Room category mapping to room class (Standard → Presidential).
- `dim_date`: Date-level info including weekend/weekday and week numbers.

🗓️ Time Period: **May–July**


