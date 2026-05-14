# Customer-Complaint-Analytics

A comprehensive data analysis project examining consumer complaints in the bank of America using Excel and Power BI.


## Table of Content

•	[Introduction](introduction)
•	(Project Description](project-description)
•	[Project Aim](project-aim)
•	[About the Dataset](about-the-dataset)
•	[Tools Used](tools-used)
•	[Methodology](methodology)
•	[Data Cleaning and Transformation](data-cleaning-and-transformation)
•	[Data Modeling](data-modeling)
•	[Data Analysis](data-analysis)
•	[Data Visualization](data-visualization)
•	[Key Insights](key-insights)
•	[Recommendations](recommendation)


## Introduction

The business observed a steady rise in customer complaints across various service channels, threatening customer satisfaction and brand reputation. This project investigates these trends to uncover root causes and improve service delivery. 


## Project Description

This project follows a structured data analysis lifecycle including problem definition, data cleaning in Microsoft Excel, and the development of interactive dashboards in Power BI to provide actionable insights for stakeholders. 


## Project Aim

The goal is to analyze customer behavior patterns, evaluate company response efficiency, and identify high-risk products and regions to support strategic decision-making. 


## About the Dataset

* Source: Bank of America Consumer Complaints dataset provided by Skills to Career (STC).
* Size: 62,516 rows and 12 columns.
* Key Fields: Complaint ID, Product, Sub-product, Issue, Date Received, Submission Channel, State, and Timely Response.


## Tools Used

* Microsoft Excel: Used for data inspection, cleaning, and handling missing values. 
* Microsoft Power BI: Used for data modeling, DAX calculations, and interactive visualization. 
* Microsoft PowerPoint: Used for dashboard wireframing and layout design. 


# Methodology

  
## Importing the Dataset

The raw data was first imported into Microsoft Excel for initial cleaning and validation. Once the dataset was finalized, it was loaded into Power BI for advanced analysis and reporting.


## Data Cleaning & Transformation

* Handled Missing Values: Replaced missing "Sub-product" with "Unknown" and missing "Sub-issue" or "Public Response" with "Not Specified." 
* Standardized Columns: Renamed "Timely Response?" to "Timely Response" and removed special characters (e.g., "?") from headers. 
* Data Type Validation: Confirmed date fields were correctly formatted and categorical fields were recognized as text. 
* Duplicate Check: Verified that the dataset contained no duplicate records. 
* Geographic Enrichment: Added a full state name column based on the assumption that abbreviations belonged to the USA. 

  
## Data Modeling

* DAX Measures: Created measures to calculate the Timely Response Rate and Total Complaint Volume. 
* Calculations: Developed logic to compare timely vs. untimely responses across different product categories. 

  
## Data Analysis

The analysis focused on several key performance indicators:

* Total Complaints: 62,516 recorded incidents.
* Response Performance: A 93.77% timely response rate across all companies. 
* Product Performance: Checking/Savings accounts identified as the most frequent source of issues. 
* Geographic Hotspots: Complaint density by state (California, Florida, Texas, New York). 


## Data Visualization


### Dashboard Page 1: Complaint Overview 

<img width="1328" height="747" alt="Complaint Overview" src="https://github.com/user-attachments/assets/73a7a589-547c-4e4f-90f8-9660f83267d5" />
 

  
### Dashboard Page 2: Company Performance 

<img width="1327" height="745" alt="Company Performance" src="https://github.com/user-attachments/assets/59d49837-c471-446d-99e9-93e491a63d61" />


## Key Insights


### Complaint Volume
A total of 62.52K customer complaints were recorded in the dataset. 

### Most Affected Product
The Checking or Savings Account category recorded the highest number of complaints, with
approximately 24.81K complaints, followed by Credit Card or Prepaid Card complaints. 

### Timely Response Performance
Companies maintained a strong customer service performance with a 93.77% timely response rate, showing that most complaints were resolved within the expected timeframe. 

### Complaint Trends
Customer complaints increased steadily from 2017 and reached their peak around 2022 before
declining slightly in 2023. 

### Common Customer Issues
The most reported issue by customers was managing an Account, followed by Incorrect Information
on Reports and Problems with Purchases. 

### Complaint Submission Channels
Most complaints were submitted through the web channel, indicating that customers prefer digital
communication channels over phone calls or emails. 

### Geographic Distribution
California recorded the highest number of complaints, followed by Florida, Texas, and New York. 

### Company Response Types
Most complaints were resolved through explanations provided by companies, while fewer
complaints resulted in monetary or non-monetary relief.


## Recommendations


### Optimize Account Management Workflows

* Finding: "Managing an Account" is the most reported issue, particularly within the Checking and Savings category. 
* Recommendation: Conduct a comprehensive audit of the digital account management interface. Implement more robust self-service features and "How-To" guides within the web portal to empower customers to resolve common tasks independently.
* Stakeholders: Product Managers, Operations Team.
* Expected Impact: Reduction in the total volume of account-related complaints and improved customer autonomy, leading to lower operational costs for manual support.

### Regional Resource Allocation

* Finding: California, Florida, Texas, and New York record the highest number of complaints.
* Recommendation: Align customer service staffing and regional training programs to match the high volume in these four states. Consider localized marketing or communication strategies to address regional concerns or regulatory differences.
* Stakeholders: Operations, Executive Leadership, Marketing.
* Expected Impact: Improved regional customer satisfaction and faster resolution times for high-volume areas.
  
### Digital Channel Enhancement

* Finding: The Web is the most frequently used channel for complaints. 
* Recommendation: Invest in the stability and user experience (UX) of the web-based complaint submission system. Integrate real-time status tracking for complaints submitted online so customers are kept informed without needing to call.
* Stakeholders: Data and Analytics Team, Product Managers.
* Expected Impact:
  Enhanced customer trust and transparency, reducing the likelihood of "follow-up" complaints across other channels.

### Quality Review of "Explanation-Only" Resolutions

* Finding: Most complaints are resolved through explanations, with very few involving relief. 
* Recommendation: Perform a quality assurance (QA) review on a sample of cases closed with "explanation" to ensure customer needs were actually met. Determine if these explanations are effectively resolving the root cause or merely closing the ticket.
* Stakeholders: Customer Service Team, Compliance and Risk Department.
* Expected Impact: Higher true resolution rates and a decrease in repeat complaints for the same issues.

### Proactive Peak Management Strategy

* Finding: Complaints peaked significantly in 2022 before a slight decline. 
* Recommendation: Analyze the specific drivers behind the 2022 surge (e.g., policy changes, external economic factors, or system outages) to create a "Peak Response Playbook" for future volatility.
* Stakeholders: Executive Leadership, Risk Management.
* Expected Impact: Better business resilience and the ability to maintain the 93.77% timely response rate even during periods of high volume. 

### Report Accuracy & Data Integrity

* Finding: "Incorrect information on reports" is a top recurring issue.
* Recommendation: Strengthen data validation protocols for customer reporting and credit reporting departments. Implement automated cross-checks to ensure data accuracy before it reaches the customer or external bureaus.
* Stakeholders: Compliance and Risk Department, Data and Analytics Team.
* Expected Impact: Reduction in high-risk complaints that could lead to legal or regulatory penalties.


## Conclusion

The analysis reveals that while the company maintains a high response rate, systemic issues in account management and digital UX are driving high volumes in specific regions. Addressing these will lower operational strain and improve long-term retention. 


## Contact Information

* LinkedIn: https://www.linkedin.com/in/emmanuel-thomeson/
* Email: thoesonemmanuel@gmail.com


