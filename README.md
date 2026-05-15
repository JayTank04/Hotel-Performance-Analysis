# Project Title: Hotel Hospitality Performance Analysis

## Project Overview

This Power BI project provides a comprehensive analysis of hotel operations and revenue performance. Focused on the hospitality sector, the dashboard enables stakeholders to track key performance indicators (KPIs) across different properties, room categories, and booking platforms. The goal is to provide data-driven insights into booking trends, room utilization, and pricing strategies to optimize revenue management.

## Key Features

* **Hospitality-Specific KPIs:** Real-time tracking of essential metrics like ADR and Occupancy.
* **Advanced DAX Modeling:** Robust calculations to handle time-series data and capacity metrics.
* **Multi-Level Analysis:** A structured approach moving from high-level portfolio performance to granular property-level diagnostics.
* **Property Performance Comparison:** Benchmarking various hotels within a group to identify top performers and underutilized assets.

---

## 📈 Custom Metrics & DAX

The project utilizes advanced DAX (Data Analysis Expressions) to create specialized hospitality metrics. These calculations allow for a deep understanding of room inventory and revenue efficiency.

### Key Performance Indicators (KPIs)

* **ADR (Average Daily Rate):** Measures the average income realized from an occupied room per day.
* **DSRN (Daily Sellable Room Nights):** Represents the total capacity of rooms available to be sold on a daily basis across the hotel(s).
* **DBRN (Daily Booked Room Nights):** Tracks the number of room nights that have been successfully booked by guests.
* **DURN (Daily Utilized Room Nights):** Measures the actual number of room nights where guests checked in and utilized the space (accounting for no-shows or cancellations).
* **Occupancy %:** The ratio of booked rooms to the total available capacity.



### Time Intelligence

The model includes a custom Calendar table to support:

* **Week-on-Week (WoW) Analysis:** Tracking booking spikes during weekends vs. weekdays.
* **Monthly Trends:** Analyzing seasonal demand fluctuations in the hospitality market.

---

## 🔍 Analytical Approach

### Level 1 Analysis: Descriptive (Executive Summary)

The Level 1 view provides a "bird's eye view" of the hotel portfolio's health.

* **Total Revenue & ADR:** Identifying the primary revenue drivers.
* **Occupancy Trends:** Visualizing capacity utilization across different months and property types.
* **Booking Platforms:** Analyzing which channels (Direct, OTA, etc.) contribute most to the DBRN.

### Level 2 Analysis: Diagnostic (Deep Dive)

The Level 2 analysis investigates the "why" behind the performance numbers.

* **Utilization Gaps:** Comparing DBRN vs. DURN to understand the impact of cancellations and no-shows on revenue.
* **Property Benchmarking:** A detailed breakdown of individual hotel performance to identify why certain properties have a higher ADR than others.
* **Revenue Leakage:** Identifying periods where DSRN was high but occupancy remained low, suggesting the need for dynamic pricing adjustments.

---

## Tools Used

* **Power BI:** Data Visualization, Modeling, and Dashboarding.
* **DAX:** Custom measure creation for hospitality analytics.

---

*This project was developed as a professional portfolio piece to showcase the application of Business Intelligence in the Hotel & Hospitality industry.*
