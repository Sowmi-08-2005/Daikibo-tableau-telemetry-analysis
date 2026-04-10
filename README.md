# Daikibo-tableau-telemetry-analysis
Data analysis project using Tableau to visualize factory downtime from telemetry data.

## Overview

This project analyzes IoT telemetry data from Daikibo factories using interactive dashboards. It helps identify unhealthy devices across factories and device types using data visualization.

## Repository Contents
Daikibo_Telemetry.twbx → Tableau packaged workbook
daikibo-telemetry-data.json → Raw dataset
README.md → Project documentation

## Dataset Description

The dataset contains telemetry information of devices across multiple factories.

## Key Fields:

Device ID → Unique identifier
Device Type → Type of machine (e.g., LaserWelder, CNC)
Factory → Factory location
Status → Healthy / Unhealthy
Temperature → Device temperature readings
Timestamp → Time of record

## Dashboard Features
## Factory-wise Analysis
Visualizes SUM of Unhealthy devices by Factory
Helps detect factories with high failure rates

## Insight:

Daikibo Factory Seiko has the highest unhealthy count
Daikibo Shenzhen is second
Daikibo Berlin is lowest

## Device Type Analysis
Displays Unhealthy count by Device Type

## Insight:

LaserWelder devices show maximum failures
Other devices have minimal issues

## Interactive Dashboard
Combined dashboard with:
Sheet 1 (Factory view)
Sheet 2 (Device view)
Includes filter action
Click a factory → filters device types

## Tools Used
Tableau Public
JSON Data Processing

## How to Use
### Option 1: 
Tableau Workbook
Download Daikibo_Telemetry.twbx
Open in Tableau Public
Explore dashboard

### Option 2: 
Using JSON File
Open Tableau Public
Connect to JSON file
Load daikibo-telemetry-data.json
Recreate visualizations if needed

## Key Learnings
Data visualization using Tableau
Working with JSON datasets
Dashboard design & interactivity
Identifying failure patterns in IoT systems

## Contributing

Pull requests are welcome. Feel free to improve visualizations or add insights.
