# AtliQ Grand Revenue Analysis

**Project Overview:**
This project was a collaboration with industry experts to analyze hospitality data for AtliQ Grand, a luxury/business hotel chain. The aim was to identify and track revenue sources and other KPIs using Power BI.

**Scenario:**
AtliQ Grands, a prominent hotel chain, faced a significant drop in market share and revenue. The management decided to leverage Business and Data Intelligence to identify the root causes and reverse the downward trend.

**Domain:** Hospitality Industry  
**Function:** Revenue Management  
**Tools Used:** Power BI

**Skills Acquired:**
- Technical: Power BI, dashboard creation, data modeling, DAX calculations.
- Core: Stakeholder engagement, business analysis, analytical mindset development.

## Project Details

### Business Objective
AtliQ aimed to incorporate Business and Data Intelligence to identify and track revenue sources.

### Problem Statement / Project Scope
- Identify data sources pertaining to revenue management.
- Clean and model the data for analysis.
- Create a revenue dashboard that measures important KPIs.
- Provide relevant filters to slice and dice the data.
- Depict both high-level and granular insights in the dashboard.

### Solution Approach
1. **Data Preparation:**
   - Imported data from 5 tables (3 dimension tables: date, hotel, room; 2 fact tables: bookings, aggregated bookings) into Power BI.
   - Cleaned and transformed the data using Power Query.
   - Created relationships between the tables in Power Pivot.

2. **DAX Measures:**
   - Created several measures to calculate KPIs such as Revenue, Total Bookings, Average Rating, Total Capacity, Total Successful Bookings, Occupancy Rate, Total Cancelled Bookings, Cancellation Rate, and Average Stay Duration.

3. **Dashboard Features:**
   - Visuals: Bar chart for revenue by platform, column chart for occupancy rate by day, doughnut chart for revenue by room type, pie chart for bookings by status, and a KPI table showing KPIs across cities and hotels.
   - Filters: Month-year, city, booking status, booking platform.
   - Interactive elements and tooltips for enhanced data exploration.

### Business Outcomes
- Mumbai generated the highest revenue while Delhi generated the least from May to July 2022.
- Higher occupancy rates during weekends across all cities suggested leveraging this trend to boost revenue.
- Identified that 75% of bookings generated revenue while 5% were no-shows.
- Compared average ratings and stay duration with industry benchmarks to evaluate performance.
- Despite Delhi's highest occupancy rate, it generated the least revenue.

### Conclusion
The revenue dashboard provided a comprehensive visual representation of AtliQ's key performance indicators. It facilitated both high-level and in-depth analysis, helping the management make data-driven decisions to improve market share and revenue.

## Screenshots
- Include screenshots of your dashboard here.

## Repository Contents
- `README.md`: Project overview and details.
- `Atliq_Grand_Revenue_Analysis.pbix`: Power BI file.
- `Presentation.pptx`: Project presentation.

## How to Use
1. Download the `.pbix` file and open it in Power BI Desktop.
2. Explore the interactive dashboard and the various visuals provided.