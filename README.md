# Hotel Bookings and Guest Behavior Analytics Dashboard
[Tableau Public: Guest Booking Behavior and Cancellation Insights Dashboard](https://public.tableau.com/app/profile/ashley.roberts5700/viz/HotelBookings_DZV/Dashboard1?publish=yes)

## Overview

This Tableau dashboard explores hotel booking patterns, guest segments, cancellation behavior, and seasonal demand trends using hospitality booking data.

The goal of the project was to transform raw operational data into interactive visualizations that support business decision-making.

## Business Questions

- Which guest segments have the highest cancellation rates?
- How does booking lead time impact cancellations?
- How do repeat and first-time guest behaviors differ?
- What seasonal trends emerge across the data?

## Tools Used

- SQL Server
- Tableau

## Dashboard Preview
Executive view of hotel booking performance, cancellations, guest segments, and booking channels:
![Dashboard Screenshot](https://github.com/ashleyhroberts/Hotel_Bookings_Analysis_Guest_Behavior/blob/main/screenshots/Hotel%20Bookings%20Dashboard%20screenshot.png)

Selecting a market segment allows users to drill into cancellation behavior by by segment and booking leadtime.

Interactive Drill-Down - Cancellation Analysis:

![Dashboard Drilldown](https://github.com/ashleyhroberts/Hotel_Bookings_Analysis_Guest_Behavior/blob/main/screenshots/Cancellation%20Drilldown%20screenshot.png)

Dashboard actions enable exploration of booking patterns across guest types.

Interactive Drill-down - Repeat Guest Behavior:

![Dashboard Drilldown](https://github.com/ashleyhroberts/Hotel_Bookings_Analysis_Guest_Behavior/blob/main/screenshots/Repeat%20Guest%20Drilldown%20screenshot.png)

## Key Insights

- OTA (Online Travel Agency) bookings exhibited higher cancellation rates than direct bookings.
- Longer booking lead times were associated with increased cancellations.
- The Groups market segment had the highest cancellation rate with the Transient and Transient Party customer types contributing more than the others.
- Peak travel months (July and August) generally aligned with higher ADR.
- Repeat guests paid substantially lower ADRs (Average Daily Rates), had shorter booking horizons and lower cancellation rates.
- Repeat guests skewed heavily toward the Corporate bookings segment which had lower ADRs and first-time guests skewed towards OTAs wich had higher ADRs.


## Files Included

- HotelBookingsDashboard.twbx
- hotel_bookings.csv
- SQL queries from Exploratory Data Analysis (EDA)
- Dashboard screenshots

## About This Project

This project was developed as part of my transition into data analytics, with a focus on transforming hospitality data into actionable business insights through visualization.
