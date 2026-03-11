# Daikibo Factory Telemetry Data Analysis

## Project Overview
This project analyzes machine telemetry data collected from four Daikibo factories. The objective was to identify which factory experienced the most machine downtime and which machines failed the most.

This project was completed as part of the Deloitte Data Analytics Job Simulation on Forage.

## Factories Analyzed
- Meiyo (Tokyo, Japan)
- Seiko (Osaka, Japan)
- Berlin (Germany)
- Shenzhen (China)

Each factory contains 9 machine types sending telemetry messages every 10 minutes.

## Tools Used
- Tableau
- JSON Dataset

## Data Analysis Steps
1. Imported telemetry JSON dataset into Tableau
2. Created calculated field "Unhealthy" to represent machine downtime
3. Built visualization showing downtime per factory
4. Built visualization showing downtime per device type
5. Created interactive dashboard linking both charts

## Key Insights
The dashboard helps identify:
- Which factory has the highest downtime
- Which machine types contribute most to failures

## Dashboard
![Dashboard](dashboard.png)

## Learning Outcome
This project helped me learn:
- Data visualization using Tableau
- Analyzing machine telemetry data
- Creating interactive dashboards
