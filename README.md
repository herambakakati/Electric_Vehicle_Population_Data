Electric Vehicle Population Data Analysis (Power BI)

Project Overview
This project analyzes Electric Vehicle (EV) Population data using Power BI to understand adoption trends, vehicle types, electric range distribution, and geographical patterns.  
The goal is to transform raw data into meaningful insights through data cleaning, modeling, KPIs, and interactive dashboards.

---

Tools & Technologies
- Power BI
- Power Query
- DAX
- CSV Dataset
- Data Visualization & Analytics

---

Data Cleaning & Preparation
The following data transformations were performed:
- Renamed vehicle type values:
  - Battery Electric Vehicle (BEV) → Battery Electric Vehicle
  - Plug-in Hybrid Electric Vehicle (PHEV) → Hybrid Electric Vehicle
- Removed records with blank vehicle locations
- Created Electric Range Bin:
  - `0–100` → Low  
  - `101–200` → Medium  
  - `>200` → High
- Extracted Latitude and Longitude from location geometry field

---

Key KPIs
- Total Vehicles
- Average Electric Range
- Total BEV Vehicles & % Share
- Total PHEV Vehicles & % Share

---

Visualizations Included
- Total Vehicles by Model Year (from 2011 onwards)
- Total Vehicles by State
- Top 10 Vehicles by Make
- Top 10 Vehicles by Model
- Vehicles by CAFV Eligibility
- Interactive navigation buttons for dashboard experience

---

Key Insights
- Rapid growth in EV adoption in recent years
- Strong dominance of Battery Electric Vehicles
- Specific states showing higher EV concentration
- Electric range improvements across newer models

