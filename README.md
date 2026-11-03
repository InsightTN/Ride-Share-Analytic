# Ride Analytics Dashboard

A comprehensive **Power BI** dashboard powered by **SQL** that provides deep insights into ride-hailing operations.

This dashboard analyzes ride demand, driver performance, revenue, customer ratings, weather impact, and location-based metrics to support data-driven decision making.

![Dashboard Preview](back.JPG)

---

## Features

### Ride Demand Analysis
- Ride demand by time block and day (Weekday / Weekend views)
- Ride demand by vehicle type

### Revenue Insights
- Total revenue with surge pricing analysis

### Customer Experience
- User rating distribution
- Payment method breakdown

### Driver Performance
- ACR (Acceptance Completion Rate) by Driver ID
- RCR and ACR by driver experience level
- Top performing driver highlight

### External Factors
- ARD and ACR by weather condition
- Location performance table (High / Medium / Low)

---

## Tech Stack

- **Power BI Desktop** – Dashboard development and visualization
- **SQL** – Data storage and querying
- **DAX** – Calculated measures and KPIs
- **Power Query** – Data transformation and cleaning

---

## Key Metrics

| Metric | Description                          |
|--------|--------------------------------------|
| ACR    | Acceptance / Completion Rate         |
| RCR    | Ride Completion Rate                 |
| ARD    | Average Ride Duration                |
| Surge  | Dynamic pricing impact on revenue    |

---

## Project Structure
<img width="588" height="563" alt="back" src="https://github.com/user-attachments/assets/cc1227de-314e-4ea7-b618-1de0945e3061" />



Ride-Analytics-Dashboard/
│
├── Ride_Analytics_Dashboard.pbix      # Power BI report file
├── SQL Scripts/
│   ├── Create_Tables.sql
│   ├── Data_Cleaning.sql
│   └── KPI_Queries.sql
├── Images/
│   └── back.JPG
├── README.md
└── LICENSE
text---

## How to Use

### Prerequisites
- Power BI Desktop (latest version recommended)
- Access to the SQL database (or the provided SQL scripts)

### Steps
1. Download or clone this repository.
2. Open `Ride_Analytics_Dashboard.pbix` in Power BI Desktop.
3. Update the data source credentials to connect to your SQL database.
4. Refresh the data.
5. Explore the interactive dashboard (Weekday / Weekend toggle, filters, etc.).

---

## SQL Data Model Overview

The dashboard is connected to a relational SQL database containing tables such as:

- `Rides`
- `Drivers`
- `Vehicles`
- `Locations`
- `Weather`
- `Payments`
- `Ratings`

Key relationships are established between these tables to enable cross-filtering and accurate KPI calculations.

---

## Future Improvements
- Real-time data refresh using DirectQuery
- Predictive demand forecasting with Power BI AI visuals
- Row-level security for different user roles
- Mobile layout optimization

---

## Author
AMOKE JOSHUA CHIBUIKEM  
(https://www.linkedin.com/in/joshua-amoke-01a4b73b4) | joshuaolaniyi518@gmail.com

---

## License
This project is open source and available under the [MIT License](LICENSE).
