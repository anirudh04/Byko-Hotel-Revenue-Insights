# Hospitality Analytics and Revenue Insights Dashboard

This repository contains a Power BI dashboard visualizing key metrics for a hospitality business. The dashboard provides insights into booking trends, revenue, occupancy, and other KPIs.

# About 
This dashboard was developed to empower data-driven decision-making for hospitality managers through insightful visual analytics.

The key objective was to build an intuitive Power BI dashboard that provides a comprehensive view of critical metrics including bookings, revenue, occupancy, sentiment, and more. The visualization capabilities of Power BI enable drilling down into granular details and interacting with the data to uncover trends and insights.

By tracking KPIs and metrics visually over time, issues can be identified early and opportunities leveraged quickly. The dashboard enhances data-informed discussions and planning. With easy filtering and segmentation, problem areas can be isolated for focused strategies.

Overall, this dashboard aims to harness the analytical power of Power BI to optimize operations, strengthen competitive positioning and boost revenues through data-backed strategies for the hospitality sector.

# Goal
The motivation behind this work was to showcase how interactive dashboards can promote data democratization across organizations. The accessibility and flexibility of Power BI make advanced analytics achievable even for smaller teams with limited data visualization expertise.

# Data
The data used for this dashboard is contained in the data folder. It includes the following files:

- **dim_date.csv**- Contains date dimension data
- **dim_hotels.csv** - Contains hotel dimension data
- **dim_rooms.csv** - Contains room dimension data
- **fact_aggregated_bookings.csv** - Contains aggregated bookings facts
- **fact_bookings.csv** - Contains detailed bookings facts
- **meta_data.txt** - provides detailed information on each column in the dataset.
- **Final metrics list.xlsx** - List of metrics used for the dashboard

# Dashboard
The Power BI dashboard is contained in **Revenue Insights Dashboard.pbix**. It connects to the CSVs in the data folder as data sources.

The dashboard includes the following visuals:
- Booking trend line chart
- Revenue trend bar chart
- Top Hotels bar chart
- Rooms availability gauge chart
- Occupancy KPI card
- ADR KPI card
- RevPAR KPI card
- Sentiment analysis tile chart
- Bookings by source pie chart
- Bookings by status donut chart
