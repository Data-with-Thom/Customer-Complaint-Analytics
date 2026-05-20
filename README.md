# Customer-Complaint-Analytics

A comprehensive data analysis project examining consumer complaints in the bank of America using Excel and Power BI.


## Table of Content

* [Introduction](#introduction)
* [Project Description](#project-description)
*	[Project Aim](#project-aim)
* [About the Dataset](#about-the-dataset)
*	[Tools Used](#tools-used)
*	[Methodology](#methodology)
*	[Data Cleaning and Transformation](#data-cleaning-and-transformation)
*	[Data Modeling](#data-modeling)
*	[Data Analysis](#data-analysis)
*	[Data Visualization](#data-visualization)
*	[Key Insights](#key-insights)
*	[Recommendations](#recommendation)


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

* Handled Missing Values: Replaced missing "Sub-product", missing "Sub-issue" or "Public Response" with "Not Specified." 
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

<img width="1326" height="747" alt="image" src="https://github.com/user-attachments/assets/38a1cfab-b181-4686-bd2c-805d904fc187" />

---

 ## Insights, Recommendations, Stakeholders, and Expected Impact

---

### 1.
<img width="251" height="160" alt="image" src="https://github.com/user-attachments/assets/c36ec41d-65af-4ccd-9530-020942292df3" />


### Insight
A total of **62,520 customer complaints** were recorded across all products and years, indicating a significant volume of customer dissatisfaction and service issues.

#### Recommendation
Implement a company-wide complaint reduction strategy by:
- Identifying root causes of the most frequent complaints.
- Improving customer service processes.
- Enhancing product usability and support systems.
- Establishing a proactive issue detection mechanism.

#### Stakeholders
- Executive Management
- Customer Experience Team
- Operations Team
- Quality Assurance Team
- Product Managers

#### Expected Impact
- Reduction in overall complaint volume.
- Improved customer satisfaction and loyalty.
- Lower operational costs associated with complaint handling.
- Enhanced brand reputation.

---

### 2. 
<img width="252" height="152" alt="image" src="https://github.com/user-attachments/assets/0a9c98bb-d59b-4549-9d7d-aa2cf7bf54c7" />


#### Insight
The company offers **9 financial products**, but complaints are heavily concentrated in only a few products, indicating uneven product performance.

##### Recommendation
Prioritize product improvement efforts on high-complaint products while maintaining strong performance in lower-complaint products.

### Stakeholders
- Product Managers
- Business Analysts
- Risk and Compliance Team
- Customer Support Team

#### Expected Impact
- Better allocation of resources.
- Faster resolution of critical product issues.
- Improved product quality and customer experience.

---

### 3. 
<img width="256" height="155" alt="image" src="https://github.com/user-attachments/assets/282cebfc-d13f-4b3f-91b3-8937b5ce1d2f" />


#### Insight
The company responds promptly to **93.77% of complaints**, demonstrating strong operational efficiency. However, approximately **6.23%** of complaints are still not handled on time.

### Recommendation
Focus on closing the remaining gap by:
- Automating complaint routing.
- Monitoring SLA performance.
- Escalating overdue complaints.
- Increasing staffing during peak periods.

#### Stakeholders
- Customer Service Team
- Operations Managers
- IT Team
- Process Improvement Team

#### Expected Impact
- Increased response rate toward 100%.
- Improved customer trust and satisfaction.
- Reduced escalation and regulatory risks.

---


### 4.
<img width="270" height="667" alt="image" src="https://github.com/user-attachments/assets/7b777825-3506-49b5-8a05-72cf7403989d" />


#### Insight
The most reported issue is **Managing an Account (15K complaints)**, followed by:
- Incorrect Information on Reports (5K)
- Problem with Purchases (4K)
- Closing an Account (3K)
- Trouble During Payment Process (3K)

This indicates that customers experience the greatest difficulties with account administration and information accuracy.

#### Recommendation
- Redesign account management workflows.
- Improve user interface and self-service tools.
- Strengthen data validation and reporting accuracy.
- Provide clearer instructions for account-related actions.

#### Stakeholders
- Product Managers
- Digital Banking Team
- Credit Reporting Team
- UX/UI Designers
- IT Development Team

#### Expected Impact
- Significant reduction in account-related complaints.
- Improved user experience.
- Greater confidence in customer information accuracy.
- Lower support workload.

---

### 5. 
<img width="813" height="231" alt="image" src="https://github.com/user-attachments/assets/92c47672-6dbc-4d72-a78c-98eb5f7fe9e7" />


#### Insight
Complaints increased steadily from **2017 to 2022**, peaking in 2022, before declining in 2023. This suggests growing operational challenges that were partially addressed in 2023.

#### Recommendation
- Analyze the factors that caused the 2022 spike.
- Document and replicate the improvements that led to the 2023 decline.
- Establish continuous monitoring of complaint trends.

#### Stakeholders
- Executive Management
- Business Intelligence Team
- Operations Team
- Compliance Team

#### Expected Impact
- Prevention of future complaint surges.
- Data-driven decision-making.
- Sustained improvement in service quality.

---

### 6. 
<img width="806" height="231" alt="image" src="https://github.com/user-attachments/assets/86a3e853-4b5f-491d-af77-0d729d7cc6b6" />


#### Insight
Complaints are concentrated in a few products:

| Product | Complaints |
|-------|-------:|
| Checking or Savings Account | 24.81K |
| Credit Card or Prepaid Card | 16.20K |
| Credit Reporting | 7.71K |
| Mortgage | 6.60K |
| Money Transfer | 3.45K |
| Debt Collection | 2.74K |
| Vehicle Loan | 0.63K |
| Payday Loan | 0.33K |
| Student Loan | 0.04K |

Checking/Savings and Credit Card products account for the majority of complaints.

#### Recommendation
- Conduct detailed product audits for the top complaint-generating products.
- Simplify product processes and improve communication.
- Introduce targeted customer education materials.

#### Stakeholders
- Product Managers
- Banking Operations Team
- Credit Card Division
- Risk Management Team
- Customer Experience Team

#### Expected Impact
- Reduction in complaints from high-risk products.
- Improved product performance and customer retention.
- Enhanced operational efficiency.

---

### Overall Summary of Recommendations

Most recommendations focus on:
- Improving account management processes.
- Prioritizing high-complaint products.
- Enhancing response times.
- Strengthening data accuracy.
- Using trend analysis to support proactive decision-making.

Together, these actions will help reduce customer complaints, improve customer satisfaction, and drive better operational and business performance.


### Dashboard Page 2: Company Performance 

<img width="1327" height="745" alt="Company Performance" src="https://github.com/user-attachments/assets/59d49837-c471-446d-99e9-93e491a63d61" />

## Key Insights


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

### Proactive Peak Management Strategy

* Finding: Complaints peaked significantly in 2022 before a slight decline. 
* Recommendation: Analyze the specific drivers behind the 2022 surge (e.g., policy changes, external economic factors, or system outages) to create a "Peak Response Playbook" for future volatility.
* Stakeholders: Executive Leadership, Risk Management.
* Expected Impact: Better business resilience and the ability to maintain the 93.77% timely response rate even during periods of high volume.


### Quality Review of "Explanation-Only" Resolutions

* Finding: Most complaints are resolved through explanations, with very few involving relief. 
* Recommendation: Perform a quality assurance (QA) review on a sample of cases closed with "explanation" to ensure customer needs were actually met. Determine if these explanations are effectively resolving the root cause or merely closing the ticket.
* Stakeholders: Customer Service Team, Compliance and Risk Department.
* Expected Impact: Higher true resolution rates and a decrease in repeat complaints for the same issues.


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


## Conclusion

The analysis reveals that while the company maintains a high response rate, systemic issues in account management and digital UX are driving high volumes in specific regions. Addressing these will lower operational strain and improve long-term retention. 


## Contact Information

* LinkedIn: https://www.linkedin.com/in/emmanuel-thomeson/
* Email: thoesonemmanuel@gmail.com


