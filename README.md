# AppTrak Analysis

## Table of Content
- [Project Overview](#project-overview)
- [Goal](#goal)
- [Objectives](#objectives)
- [Tools Used](#tools-used)
- [Data Preparation](#data-preparation)
- [KPIs](#kpis)  
- [Insights](#insights)
- [Data Visualization](#data-visualization)
- [Conclusion](#conclusion)
  
## Project Overview
AppTrak Analysis is a personal data analytics project that tracks and visualizes how I use apps on my phone. Using a custom iOS shortcut, the project logs each app session’s details (date, time, location, network type, battery status) and automatically saves them into a CSV file. This dataset is then transformed into an interactive Excel dashboard for analysis.

## Goal
To analyze my own app usage data and discover patterns in how, when and where I use different apps.

## Objectives
- To build a custom app usage dataset directly from my phone
- To clean and enrich data for deeper analysis
- To visualize insights to understand usage by:
  1. Location
  2. Weekday
  3. Daytime
  4. Battery status
  5. Network details/type
  6. Monthly trends
- To identify habits and potential areas for digital well-being improvements.

 ## Tools Used
  - iOS Shortcuts: manual logging of app usage
  - iCloud Drive: storing the csv log file
  - Excel: data analysis and dashboard creation
  - Power Query: data cleaning and transformation

  ## Data Preparation
  - Built a custom shortcut to run when opening an app
  - Collected
    - Application name
    - Date & time
    - Location (city)
    - Network details (Wi-Fi/mobile)
    - Battery status
  - Saved each log entry to a csv file on iCloud Drive
  - Imported csv into Excel
  - Used power query to:
     1. Remove duplicates and fix column types
     2. Add weekday, month and daytime segment columns.
  
  ## KPIs
  ## Insights
  ## Data Visualization
  ## Conclusion
  
