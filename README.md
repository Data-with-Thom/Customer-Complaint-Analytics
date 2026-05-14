# Customer-Complaint-Analytics
A comprehensive data analysis project examining consumer complaints in the bank of America using Excel and Power BI.

## Introduction
The business observed a steady rise in customer complaints across various service channels, threatening customer satisfaction and brand reputation. This project investigates these trends to uncover root causes and improve service delivery. 


## Project Description
This project follows a structured data analysis lifecycle including problem definition, data cleaning in Microsoft Excel, and the development of interactive dashboards in Power BI to provide actionable insights for stakeholders. 


## Project Aim
The goal is to analyze customer behavior patterns, evaluate company response efficiency, and identify high-risk products and regions to support strategic decision-making. 


## About the Dataset
### Source:
  Finance Industry Consumer Complaints dataset provided by Skills to Career (STC).
### Size:
  62,516 rows and 12 columns.
### Key Fields:
  Complaint ID, Product, Sub-product, Issue, Date Received, Submission Channel, State, and Timely Response.


## Tools Used
### Microsoft Excel:
  Used for data inspection, cleaning, and handling missing values. 
### Microsoft Power BI:
  Used for data modeling, DAX calculations, and interactive visualization. 
### Microsoft PowerPoint:
  Used for dashboard wireframing and layout design. 

  
## Importing the Dataset
The raw data was first imported into Microsoft Excel for initial cleaning and validation. Once the dataset was finalized, it was loaded into Power BI for advanced analysis and reporting.


## Data Cleaning & Transformation
### Handled Missing Values:
  Replaced missing "Sub-product" with "Unknown" and missing "Sub-issue" or "Public Response" with "Not Specified." 
### Standardized Columns:
  Renamed "Timely Response?" to "Timely Response" and removed special characters (e.g., "?") from headers. 
### Data Type Validation:
  Confirmed date fields were correctly formatted and categorical fields were recognized as text. 
### Duplicate Check: 
  Verified that the dataset contained no duplicate records. 
### Geographic Enrichment:
  Added a full state name column based on the assumption that abbreviations belonged to the USA. 

  
## Data Modeling
### DAX Measures:
  Created measures to calculate the Timely Response Rate and Total Complaint Volume. 
### Calculations: 
  Developed logic to compare timely vs. untimely responses across different product categories. 

  
## Data Analysis
The analysis focused on several key performance indicators:

### Total Complaints:
  62,516 recorded incidents. 
### Response Performance:
  A 93.77% timely response rate across all companies. 
### Product Performance:
  Checking/Savings accounts identified as the most frequent source of issues. 
### Geographic Hotspots:
  Complaint density by state (California, Florida, Texas, New York). 


## Data Visualization
### Dashboard Page 1: Complaint Overview 
#### KPI Cards: Total Complaints, Affected Products, and Timely Response Rate. 
•	Line Chart: Complaint trends over time (showing a peak in 2022). 
•	Bar Chart: Most common complaint issues and complaints by product. 
•	Slicers: Product and State filters for deep-dive analysis. 
Dashboard Page 2: Company Performance 
•	Doughnut Chart: Company response types (e.g., "Closed with explanation"). 
•	Bar Chart: Complaints by submission channel (Web, Phone, etc.). 
•	Map/Bar Chart: Regional distribution of complaints by state. 
11. Key Insights
•	Peak Volume: Complaints rose steadily from 2017, peaking in 2022. 
•	Primary Issue: "Managing an Account" is the most frequent customer pain point. 
•	Dominant Channel: Customers prefer digital communication, with most complaints submitted via the Web. 
•	Resolution Type: Most cases are resolved via "explanation" rather than monetary relief. 
12. Recommendations
•	Process Improvement: Audit digital account management portals to reduce "Managing an Account" friction. 
•	Resource Allocation: Increase support staff or localized training for California and Florida. 
•	UX Enhancement: Improve the stability of the Web submission channel to maintain customer trust. 
•	Quality Assurance: Review "explanation-only" resolutions to ensure root causes are truly addressed. 
13. Conclusion
The analysis reveals that while the company maintains a high response rate, systemic issues in account management and digital UX are driving high volumes in specific regions. Addressing these will lower operational strain and improve long-term retention. 
14. Contact Information
•	LinkedIn: [Your LinkedIn Profile Link]
•	Email: [Your Professional Email]
________________________________________
Project completed as part of the STC 5-Week Mentorship 3.0. Team: Lamidi Habeebullah, Emmanuel Thomeson, Omolara Buhari. 

