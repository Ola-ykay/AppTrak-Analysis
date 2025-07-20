# AppTrak Analysis

## Table of Content
- [Project Overview](#project-overview)
- [Goal](#goal)
- [Objectives](#objectives)
- [Tools Used](#tools-used)
- [Data Preparation](#data-preparation)
- [KPIs](#kpis)  
- [Insights](#insights)
- [Questions Discovered](#questions-discovered)
- [Data Snapshots](#data-snapshots)
- [Conclusion](#conclusion)
  
## 🎯Project Overview
AppTrak Analysis is a personal data analytics project that tracks and visualizes how I use applications on my phone. Using a custom iOS shortcut, the project logs each app session’s details (date, time, location, network type, battery status) and automatically saves them into a CSV file. This dataset is then transformed into an interactive Excel dashboard for analysis.

## 📌Goal
To analyze my own app usage data and discover patterns in how, when and where I use different apps.

## ✅Objectives
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

 ## 🛠Tools Used
  - iOS Shortcuts: manual logging of app usage
  - iCloud Drive: storing the csv log file
  - Excel: data analysis and dashboard creation
  - Power Query: data cleaning and transformation

  ## 🔄Data Preparation
  - Built a custom shortcut to run when opening some apps 
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
  - Built an Excel Dashboard with:
     1. Pivot tables
     2. Slicers
  
  ## 📊KPIs
  - Number of Apps
  - Average Battery Status
  - Total App Usage
  - Top 10 most Used Apps
  - App Usage by Day
  - App Usage by Location
  - App Usage by Network Details
  - App Usage by Daytime
  - App Usage by Battery Status
  - App Usage Distribution by Daytime
    
  ## 🔍Insights
  - Whatsapp is the most frequently used app overall
  - Monday shows the highest app uasge
  - Sandown is the top location where app usage is most concentrated
  - App usage peaked in April
  - Most app sessions occur on WiFi(Home and work)
  - App usage is highest in the morning hours
  - Yes, high-battery periods show use of media-heavy apps (like Music, audiomack, X)
    
  ## 🔍Questions Discovered
  - Which app do I use the most?
  - Which day do I spend most time on apps?
  - Where do I use the apps the most?
  - How does my app usage change month by month?
  - Do I use more apps on WiFi or mobile data?
  - What time of day am I most active?
  - Does battery level influence which app I open?
  - At what time of day do I use each app the most?

  ## Data Snapshots
  ![Table](https://github.com/Ola-ykay/AppTrak-Analysis/blob/main/Apptrak-table.png)
  ![Raw-Data](https://github.com/Ola-ykay/AppTrak-Analysis/blob/main/Apptrak-raw-data.png)
  ![Power-Query-Table](https://github.com/Ola-ykay/AppTrak-Analysis/blob/main/Apptrak-power-query.png)
  ![Analysis](https://github.com/Ola-ykay/AppTrak-Analysis/blob/main/Apptrak-analysis.png)
  ![Dashboard](https://github.com/Ola-ykay/AppTrak-Analysis/blob/main/Apptrak-dashboard.png)
  
  ## 🚀Conclusion

