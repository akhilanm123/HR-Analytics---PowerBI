# HR-Analytics---PowerBI and Excel
## Project Overview
This **HR Analytics Dashboard** is designed to analyze and visualize employee attendance trends using **Power BI**. It provides insights into key HR metrics, such as:

- **Presence %** – Overall attendance trends
- **Work From Home (WFH) %** – Remote work frequency
- **Sick Leave (SL) %** – Employee absenteeism patterns
- **Day-wise Attendance Analysis** – Identifies trends across weekdays
- **Employee-wise Insights** – Tracks individual attendance behavior
  
The raw attendance data, stored in **CSV format**, was cleaned, transformed, and modeled using **Power Query Editor**and **DAX (Data Analysis Expressions)**.
## Tools & Technologies Used + Resources
- **Power BI** – Data visualization and dashboard creation
     -  **Dashboard Interaction**:  <a href="https://github.com/akhilanm123/HR-Analytics---PowerBI/blob/main/HR%20Analytics.pbix">HR Analytics</a>
- **Power Query Editor** – Data cleaning and transformation
- **DAX (Data Analysis Expressions)** – Custom measures and calculated columns
- **CSV Files** – Data source
  -  <a href="https://github.com/akhilanm123/HR-Analytics---PowerBI/blob/main/Attendance%20Sheet%202022-2023_Masked.xlsx">Attendance Dataset</a>
##  Insights & Technical Implementation
#### Data Preparation & Cleaning
- Used **Power Query Editor** to:
          - Convert raw attendance logs into a structured format
          - Remove inconsistencies and null values
          - Create a relationship model for analysis
#### Key Metrics & DAX Measures
- **Presence %** → (Days Present / Total Working Days) * 100
- **WFH %** → (Work From Home Days / Total Working Days) * 100
- **SL %** → (Sick Leave Days / Total Working Days) * 100
- **Moving Averages & Trend Lines** → Implemented using DAX to visualize fluctuations
## Dashboard Features

The HR Analytics Dashboard provides a detailed view of employee attendance patterns using interactive visuals, slicers, and key performance indicators (KPIs). Below are the core features that enhance usability and analytical depth.
![HR Analytics](https://github.com/user-attachments/assets/f74b5493-3bc9-47d8-8b19-54ead705b3f9)
### 1. Key Metrics & KPIs Overview: 
- **Presence %** – The overall percentage of days employees were present.
- **WFH %** – The proportion of work-from-home (WFH) days recorded.
- **SL %** – The percentage of sick leave (SL) taken.

These KPIs help HR teams quickly assess overall attendance trends without diving into detailed reports.

### 2. Employee-Wise Attendance Breakdown
- A table lists individual employees along with their respective **Presence %, WFH %, and SL %**.
- Enables comparison of attendance trends across employees.
- Helps in identifying potential attendance issues for specific employees.

### 3. Time-Series Trend Analysis
- The dashboard includes three interactive line charts tracking attendance trends over time:
-  **Presence % Trend** – Tracks fluctuations in the daily presence percentage.
-  **WFH % Trend** – Highlights peaks in work-from-home days over months.
- **SL % Trend** – Captures patterns in sick leave usage.

Each chart features moving averages (dotted trendlines) calculated using DAX to provide a smoothed-out view of attendance behavior.

### 4. Day-of-Week Attendance Insights
- Tables on the right side of the dashboard display average attendance metrics categorized by weekdays.
- **Presence % by Day** – Identifies which weekdays have the highest or lowest attendance.
- **WFH % by Day** – Reveals preferred work-from-home days.
- **SL % by Day** – Detects trends in sick leave usage (e.g., frequent Monday absenteeism).

These insights help HR teams optimize scheduling, identify patterns of absenteeism, and make data-driven policy adjustments.

###  5. Interactive Slicers & Filters
- **Date Range Selector** – Users can filter attendance trends for specific time periods (e.g., April–June).
- **Employee Selection Filter** – Allows HR personnel to analyze individual employee attendance patterns.
- **Department/Team-Based Filtering** – Enables deeper insights into team-specific trends.

### 6. Attendance Data Table

A raw data table is included at the bottom of the dashboard, displaying **daily attendance status (P for Present, HPI for Half-Present, etc.)** for each employee.
- Serves as a reference for analyzing attendance records at a granular level.
- Can be used to validate summary statistics against raw data.
##  Conclusion

The **HR Analytics** Dashboard transforms raw attendance data into  **actionable insights**, helping HR teams make  **data-driven decisions** with ease. By leveraging  **Power BI, Power Query, and DAX**, this interactive dashboard not only simplifies attendance tracking but also uncovers patterns that can  **optimize workforce productivity and policy planning**.

With  **real-time filtering, trend analysis, and dynamic visualizations**, this tool empowers organizations to enhance employee management, reduce absenteeism, and foster a more efficient work environment.



