# Daikibo-tableau-telemetry-analysis
Data analysis project using Tableau to visualize factory downtime from telemetry data.

## Overview
- This project analyzes IoT telemetry data from Daikibo factories using interactive dashboards.

- It helps identify unhealthy devices across factories and device types using data visualization.

## Repository Contents
1. **Daikibo_Telemetry.twbx** → Tableau packaged workbook

2. **daikibo-telemetry-data.json** → Raw dataset

3. **README.md** → Project documentation

## Dataset Description
The dataset contains telemetry information of devices across multiple factories.

## Key Fields:
1. **Device ID** **→** Unique identifier

2. **Device Type** **→** Type of machine (e.g., LaserWelder, CNC)

3. **Factory →** Factory location

4. **Status →** Healthy / Unhealthy

5. **Temperature →** Device temperature readings

6. **Timestamp →** Time of record

## Dashboard Features

### Factory-wise Analysis
- Visualizes SUM of Unhealthy devices by Factory

- Helps detect factories with high failure rates

### Insight:
- Daikibo Factory Seiko has the highest unhealthy count

- Daikibo Shenzhen is second

- Daikibo Berlin is lowest

### Device Type Analysis
Displays Unhealthy count by Device Type

### Insight:
- LaserWelder devices show maximum failures

- Other devices have minimal issues

## Interactive Dashboard
- Combined dashboard with:

  - Sheet 1 (Factory view)

  - Sheet 2 (Device view)

- Includes filter action

  - Click a factory → filters device types

## Tools Used
1. Tableau Public

2. JSON Data Processing

## How to Use
### Option 1: 
1. Tableau Workbook

2. Download **Daikibo_Telemetry.twbx**

3. Open in Tableau Public

4. Explore dashboard

### Option 2: 
1. Using **JSON File**

2. Open Tableau Public

3. Connect to JSON file

4. Load daikibo-telemetry-data.json

5. Recreate visualizations if needed

## Key Learnings
- Data visualization using Tableau

- Working with JSON datasets

- Dashboard design & interactivity

- Identifying failure patterns in IoT systems

## Contributing

Pull requests are welcome. Feel free to improve visualizations or add insights.
