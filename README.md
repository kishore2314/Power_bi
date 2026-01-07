🏨 Atliq Grands – Hotel Performance Analytics Dashboard
📌 Project Overview

This project focuses on building an interactive Power BI dashboard to analyze the operational and financial performance of Atliq Grands, a hospitality business. The dashboard enables stakeholders to track key metrics such as revenue, occupancy, booking behavior, cancellations, and revenue realization across cities, properties, platforms, and time.

The goal of the project is to deliver data-driven insights that support better business and operational decisions in the hospitality domain.

🎯 Objectives

Analyze revenue and occupancy trends across different cities and hotels

Identify booking behavior patterns by platform

Measure cancellation impact and revenue realization efficiency

Track month-on-month (MoM) performance changes

Compare weekday vs weekend occupancy behavior

🛠 Tools & Technologies

Power BI Desktop

DAX (Data Analysis Expressions)

Power Query

CSV datasets

🧱 Data Model

The project uses a Star Schema data model for performance and scalability.

Fact Tables

fact_bookings – Booking-level transactional data (revenue, platform, booking status)

fact_aggregated_bookings – Aggregated occupancy and capacity data

Dimension Tables

dim_date – Date, month, week, and day type (weekday/weekend)

dim_hotels – Property and city details

dim_rooms – Room category information

📊 Key KPIs Implemented

Total Revenue (₹ Millions)

Occupancy Rate (%)

Cancellation Rate (%)

Revenue Realization Rate (%)

Month-on-Month Revenue Change (%)

Month-on-Month Occupancy Change (%)

Total Bookings

⚠️ Customer ratings were not available in the dataset. Instead of introducing dummy data, Revenue Realization Rate was used as a more reliable and business-relevant KPI.

📈 Dashboard Insights

The dashboard provides insights through:

Revenue and occupancy comparison by city

Weekly trend analysis of occupancy

Property-level performance summary

Platform-wise booking share

Weekday vs weekend occupancy behavior

Interactive slicers for city, month, platform, and property

🧠 Key Learnings

Designing a clean star-schema model improves performance and clarity

DAX measures should be used for business logic instead of Power Query aggregations

Time-intelligence functions require a proper date dimension

Maintaining data integrity is more important than matching a mockup visually

Replacing unavailable KPIs with meaningful alternatives improves analytical quality

🚀 Business Impact

Helps identify top-performing cities and properties

Highlights revenue leakage due to cancellations

Reveals platform dependency for bookings

Supports demand planning and operational strategy
