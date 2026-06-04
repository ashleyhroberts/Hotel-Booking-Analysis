# Hotel Booking Analysis: Guest Behavior Dashboard
[Tableau Public: Guest Booking Behavior and Cancellation Insights Dashboard](https://public.tableau.com/app/profile/ashley.roberts5700/viz/HotelBookings_DZV/Dashboard1?publish=yes))

## Overview

This Tableau dashboard analyzes hotel booking patterns, guest segments, cancellation behavior, and seasonal demand trends using hospitality booking data.

The goal of the project was to transform raw operational data into interactive visualizations that support business decision-making.

## Business Questions

- Which guest segments have the highest cancellation rates?
- How does booking lead time impact cancellations?
- How do repeat and first-time guest behaviors differ?
- What seasonal trends emerge across the data?

## Tools Used

- SQL Server
- Tableau

## Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Dashboard Design
- Customer Segmentation
- KPI Analysis
- Business Insight Generation
- Interactive Data Visualization

## Executive Dashboard

**Overview of hotel booking performance, cancellations, guest segments, and booking channels:**

![Dashboard Screenshot](https://github.com/ashleyhroberts/Hotel_Bookings_Analysis_Guest_Behavior/blob/main/screenshots/Hotel%20Bookings%20Dashboard%20screenshot.png)

## Interactive Drill-Down - Cancellation Analysis:

Selecting a market segment allows users to drill into cancellation behavior by segment and booking lead time.

![Dashboard Drilldown](https://github.com/ashleyhroberts/Hotel_Bookings_Analysis_Guest_Behavior/blob/main/screenshots/Cancellation%20Drilldown%20screenshot.png)

## Interactive Drill-Down - Repeat Guest Behavior:

Dashboard actions enable exploration of booking patterns across guest types.

![Dashboard Drilldown](https://github.com/ashleyhroberts/Hotel_Bookings_Analysis_Guest_Behavior/blob/main/screenshots/Repeat%20Guest%20Drilldown%20screenshot.png)

## Additional Exploratory Analysis: Repeat Guest ADR

A supplemental analysis was developed to investigate potential drivers behind the lower Average Daily Rate (ADR) observed among Repeat Guests during the primary dashboard analysis.

![ADR Dashboard](https://github.com/ashleyhroberts/Hotel_Bookings_Analysis_Guest_Behavior/blob/main/screenshots/ADR%20by%20Segment.png)

## Key Insights

Exploratory analysis of the dashboard revealed several meaningful patterns in guest behavior and booking characteristics:

- OTA (Online Travel Agency) bookings exhibited higher cancellation rates than direct bookings.
- Longer booking lead times were associated with increased cancellations.
- The Groups market segment had the highest cancellation rate, with the Transient and Transient Party customer types contributing more heavily than other segments.
- Peak travel months (July and August) generally aligned with higher ADR.
- Repeat guests paid substantially lower ADRs, had shorter booking lead times, and exhibited lower cancellation rates.
- Repeat guests skewed heavily toward the Corporate market segment, which generally had lower ADRs, while first-time guests skewed toward OTA channels, which exhibited higher ADRs.


## Files Included

- HotelBookingsDashboard.twbx
- hotel_bookings.csv
- SQL queries from Exploratory Data Analysis (EDA)
- Dashboard screenshots

## About This Project

This project was developed as part of my transition into data analytics, with a focus on transforming hospitality data into actionable business insights through visualization. It also provided an opportunity to practice exploratory analysis by investigating emerging questions discovered during the dashboard development process.
