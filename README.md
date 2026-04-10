🏠 Australian Property Market Analysis — End-to-End BI Solution
Project Overview
A full end-to-end Business Intelligence solution built on 32,000+ Australian property records, developed as the final Advanced Sprint project during a Data Analytics Internship at MVP Studio, Brisbane (2024–2025).
This project covers the complete BI pipeline — from raw data ingestion and ETL, through data warehousing and modelling, to interactive Power BI dashboards integrated with SSRS paginated reporting.
---
Business Questions Answered
What are house values across different states, cities, and suburbs?
How do rental values compare across regions?
What is the relationship between property values, nearby schools, transport, and crime statistics?
How can stakeholders drill through from a high-level dashboard into detailed paginated reports?
---
Solution Architecture
```
Raw Excel Data
      ↓
Data Cleaning & Transformation (ETL)
      ↓
Data Warehouse (Data Model)
      ↓
SSRS Paginated Reports (deployed to SSRS Web Portal)
      ↓
Power BI Interactive Dashboard (linked to SSRS reports)
```
---
Dashboard Pages
Page	Description
🏡 House Value	Property prices by state, city, and suburb with drill-through to SSRS
🏘️ Rental Value	Rental market analysis with regional comparisons
🎓 School	Proximity and distribution of schools by suburb
🚌 Transport	Transport accessibility across locations
🔒 Crime Info	Crime statistics overlaid with property data
Each dashboard page includes a hyperlink that passes state, city, and suburb parameters directly into the SSRS paginated report for detailed drill-through analysis.
---
Tools & Technologies
Tool	Usage
Power BI Desktop	Interactive dashboards, DAX measures, drill-through hyperlinks
Power Query	Data transformation and cleansing
DAX	Calculated measures and KPIs
SSRS	Paginated reports deployed to SSRS Web Portal
SQL Server	Data warehouse and data modelling
Excel	Raw data source and initial preparation
Python / SQL	Data cleaning and pre-processing
---
Key Features
End-to-end BI pipeline from raw data to interactive reporting
SSRS integration — Power BI dashboard pages link directly to SSRS reports, passing location parameters dynamically
Multi-dimensional analysis — property values analysed alongside schools, transport, and crime data
Data warehouse design — structured data model built to support scalable reporting
---
Skills Demonstrated
`Power BI` `DAX` `Power Query` `SSRS` `ETL` `Data Warehousing` `Data Modelling` `SQL` `Data Cleaning` `Data Visualisation` `Stakeholder Reporting` `Excel`
---
Dataset
Records: 32,000+ Australian property transactions
Sources: Multiple Excel files consolidated via ETL pipeline
Fields include: suburb, city, state, house value, rental value, school data, transport data, crime statistics
---
Author
Mubin Fathima Johnkhan  
Data Analyst | Brisbane, QLD  
📧 jmubinfathima@gmail.com  
🔗 LinkedIn
---
Completed as part of the BI Developer/Data Analyst Advanced Sprint at MVP Studio, Brisbane (2024–2025).
