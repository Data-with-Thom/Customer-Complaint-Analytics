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


## Dashboard Page 1: Complaint Overview 

<img width="1326" height="747" alt="image" src="https://github.com/user-attachments/assets/38a1cfab-b181-4686-bd2c-805d904fc187" />

---

 ## Insights, Recommendations, Stakeholders, and Expected Impact

---

### 1.
<img width="251" height="160" alt="image" src="https://github.com/user-attachments/assets/c36ec41d-65af-4ccd-9530-020942292df3" />


#### Insight
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


## Dashboard Page 2: Company Performance 

<img width="1327" height="745" alt="Company Performance" src="https://github.com/user-attachments/assets/59d49837-c471-446d-99e9-93e491a63d61" />

## Insights, Recommendations, Stakeholders, and Expected Impact

---

### 1. Chart: Company Response to Customer Types
<img width="740" height="205" alt="image" src="https://github.com/user-attachments/assets/3ba5c8e6-1d1f-4221-a4b8-b76d41d3267d" />


#### Insight
The majority of complaints (**41.04K**) were **closed with an explanation**, indicating that many customer issues were resolved through clarification rather than compensation.

Other outcomes include:
- Closed with monetary relief: **14.70K**
- Closed with non-monetary relief: **5.27K**
- In progress: **1.49K**
- Closed: **0.01K**

This suggests that misunderstandings, communication gaps, and lack of customer awareness may be major drivers of complaints.

#### Recommendation
- Improve customer communication and transparency.
- Enhance FAQs, self-service portals, and customer education resources.
- Analyze cases requiring monetary relief to identify recurring operational failures.
- Reduce the number of unresolved ("In Progress") complaints through faster case management.

#### Stakeholders
- Customer Experience Team
- Customer Support Team
- Product Managers
- Compliance Team
- Operations Managers

#### Expected Impact
- Reduction in repeat complaints.
- Lower compensation costs.
- Faster complaint resolution.
- Increased customer trust and satisfaction.

---

### 2. Chart: Timely vs Untimely Responses
<img width="740" height="210" alt="image" src="https://github.com/user-attachments/assets/8bc5d07d-d8f6-4636-acb1-7c6c9bc83389" />


#### Insight
Out of all complaints:
- **58.62K (93.77%)** received timely responses.
- **2.40K (3.84%)** received untimely responses.
- A small percentage were not specified.

The organization demonstrates strong responsiveness, but delayed responses still affect thousands of customers.

#### Recommendation
- Implement automated complaint routing and escalation systems.
- Monitor Service Level Agreements (SLAs) in real time.
- Prioritize high-risk and overdue complaints.
- Increase staffing during peak complaint periods.

#### Stakeholders
- Customer Service Department
- Operations Team
- IT Department
- Executive Management

#### Expected Impact
- Improved customer experience.
- Increased customer retention.
- Reduced complaint escalation.
- Better regulatory compliance.

---

### 3. Chart: Complaints by Submission Channel
<img width="741" height="206" alt="image" src="https://github.com/user-attachments/assets/5549fc82-fa07-405a-a576-56cc32b69bad" />


#### Insight
The **Web channel dominates complaint submissions**, accounting for approximately **45.42K complaints**, significantly higher than all other channels.

| Channel | Complaints |
|----------|-----------:|
| Web | 45.42K |
| Referral | 10.77K |
| Phone | 4.68K |
| Postal Mail | 1.32K |
| Fax | 0.23K |
| Web Referral | 0.09K |
| Email | 0.00K |

This indicates that customers strongly prefer digital channels when reporting issues.

#### Recommendation
- Invest in improving web platform performance and usability.
- Add chatbot and self-service support capabilities.
- Optimize complaint submission forms to capture complete information.
- Monitor website issues proactively to prevent customer frustration.

#### Stakeholders
- Digital Experience Team
- IT Department
- Customer Service Team
- Product Development Team

#### Expected Impact
- Faster complaint resolution.
- Reduced customer effort.
- Better digital customer experience.
- Increased operational efficiency.

---

### 4. Chart: Complaints by State
<img width="742" height="203" alt="image" src="https://github.com/user-attachments/assets/e02d7eb9-dc1c-48d2-aabc-611b8b7ea023" />


#### Insight
Complaints are concentrated in a few states:

| State | Complaints |
|---------|----------:|
| California | 13.71K |
| Florida | 6.49K |
| Texas | 4.69K |
| New York | 4.44K |
| Georgia | 2.92K |
| New Jersey | 2.66K |
| Illinois | 2.27K |
| Massachusetts | 2.14K |
| Maryland | 1.96K |
| Virginia | 1.73K |

California alone accounts for more than double the complaints recorded in Florida, suggesting either:
- A larger customer base,
- Higher product adoption,
- Or more significant customer experience challenges.

#### Recommendation
- Conduct regional root-cause analysis in high-complaint states.
- Deploy targeted customer support initiatives in California and Florida.
- Compare operational practices between high-performing and low-performing states.
- Increase monitoring of regional customer feedback.

#### Stakeholders
- Regional Operations Managers
- Customer Experience Team
- Product Managers
- Business Intelligence Team
- Executive Leadership

#### Expected Impact
- Better regional service quality.
- Reduced complaint concentration in high-risk states.
- Improved customer satisfaction across regions.
- More efficient allocation of support resources.

---

### Executive Summary

#### Key Findings
1. Most complaints are resolved through explanations rather than financial compensation.
2. The company maintains a strong timely response rate of **93.77%**.
3. The web platform is the dominant complaint submission channel.
4. California represents the largest concentration of complaints.
5. A small but significant number of complaints still experience delayed responses.

#### Strategic Priorities
- Improve digital customer experience.
- Reduce complaint volumes in high-risk states.
- Strengthen proactive customer communication.
- Optimize complaint handling processes.
- Continue improving response time performance.

#### Overall Business Impact
Implementing these recommendations can lead to:
- Higher customer satisfaction.
- Lower complaint handling costs.
- Improved operational efficiency.
- Stronger regulatory compliance.
- Increased customer loyalty and retention.



## Conclusion

The analysis reveals that while the company maintains a high response rate, systemic issues in account management and digital UX are driving high volumes in specific regions. Addressing these will lower operational strain and improve long-term retention. 


## Contact Information

* LinkedIn: https://www.linkedin.com/in/emmanuel-thomeson/
* Email: thoesonemmanuel@gmail.com


