# Hospitality-Dashboard
[View My Power BI Dashboard](https://app.powerbi.com/reportEmbed?reportId=e7f49df6-d0b9-4286-a569-81a2d18410ca&autoAuth=true&ctid=2109ce83-7de4-4471-91ff-2053f90a1fd9)



# 🏨 Hospitality Insights: Global Hotel Bookings Dashboard
A dynamic, interactive data visualization tool built to explore hotel booking trends across multiple cities, focusing on occupancy rates, revenue analysis, guest preferences, and hotel performance metrics.

## Short Description / Purpose
The Hospitality Insights Dashboard is a Power BI report designed to analyze booking data for hotels across various cities, providing insights into occupancy, revenue, guest demographics, and booking patterns. It serves hotel managers, tourism analysts, and business strategists to optimize operations and enhance customer experiences.

## Tech Stack
The dashboard was built using the following tools and technologies:  
• 📊 **Power BI Desktop** – Primary platform for creating interactive reports and visualizations.  
• 📂 **Power Query** – Used for data transformation, cleaning, and preparation of CSV datasets.  
• 🧠 **DAX (Data Analysis Expressions)** – Used for calculated measures, dynamic aggregations, and conditional logic.  
• 📝 **Data Modeling** – Relationships established among tables (dim_date, dim_hotels, dim_rooms, fact_aggregated_bookings, fact_bookings) for seamless cross-filtering.  
• 📁 **File Format** – .pbix for development and .png for dashboard previews.

## Data Source
**Source**: Internal hotel booking database (provided as 5 CSV files: dim_date, dim_hotels, dim_rooms, fact_aggregated_bookings, fact_bookings).  
**Description**: The dataset includes booking details for hotels across multiple cities, covering dates in May, June, and July 2022. It includes hotel properties, room types, booking statuses, revenue metrics, and guest information, enabling comprehensive analysis of hospitality trends.

## Features / Highlights

### Business Problem
AtliQ Grands owns multiple five-star hotels across India. They have been in the hospitality industry for the past 20 years. Due to strategic moves from other competitors and ineffective decision-making in management, AtliQ Grands are losing its market share and revenue in the luxury/business hotels category. As a strategic move, the managing director of AtliQ Grands wanted to incorporate "Business and Data Intelligence" to regain their market share and revenue. However, they do not have an in-house data analytics team to provide them with these insights.

Their revenue management team had decided to hire a third-party service provider to assist them with insights from their historical data.

### Goal of the Dashboard
To provide an interactive visual platform that:  
- Enables hotel managers to monitor occupancy, revenue, and guest satisfaction metrics.  
- Supports strategic decisions for pricing, marketing, and resource allocation.  
- Uncovers trends in booking patterns, room preferences, and cancellation rates across cities and hotel categories.

### Walkthrough of Key Visuals
- **Key KPIs (Top Section)**  
  - Total hotels analyzed.  
  - Average occupancy rate (%).  
  - Total revenue generated and realized.  
  - Cancellation rate (%).  
  - Average guest ratings.  
- **City and Hotel Category Filter Panel**  
  - Interactive slicers for filtering by city (e.g., Mumbai, Delhi) and hotel category (Luxury, Business).  
- **Occupancy by City (Bar Chart)**  
  - Displays occupancy rates across cities, highlighting high-performing regions.  
- **Revenue Trends by Month (Line Chart)**  
  - Tracks revenue generated and realized over May, June, and July, segmented by week or day type (Weekend/Weekday).  
- **Room Category Performance (Stacked Bar Chart)**  
  - Shows booking distribution across room types (RT1, RT2, RT3, RT4) and classes (Standard, Elite, Premium, Presidential).  
- **Booking Platform Analysis (Pie Chart)**  
  - Visualizes the share of bookings by platform (e.g., online, direct, third-party).  
- **Guest Ratings and Cancellations (Dual Axis Chart)**  
  - Compares average ratings with cancellation rates to identify correlations between guest satisfaction and booking outcomes.  
- **Revenue by Hotel (Grouped Bar Chart)**  
  - Compares revenue generated vs. realized across hotels, highlighting financial impacts of cancellations.

### Business Impact & Insights
- **Revenue Optimization**: Hotels can adjust pricing strategies based on demand trends and cancellation patterns.  
- **Operational Efficiency**: Identify underperforming room types or properties to optimize resource allocation.  
- **Customer Experience**: Use guest ratings to improve services and reduce cancellations.  
- **Market Analysis**: Tourism boards and hotel chains can evaluate city-level performance to target marketing efforts.

## Screenshots / Demos
![Dashboard Preview](https://github.com/stevensie09/Hospitality-Dashboard/blob/main/Hospitality%20Dashboard%201.png)
![Dashboard Preview](https://github.com/stevensie09/Hospitality-Dashboard/blob/main/Hospitality%20Dashboard%202.png)
![Dashboard Preview](https://github.com/stevensie09/Hospitality-Dashboard/blob/main/Hospitality%20Dashboard%203.png)

