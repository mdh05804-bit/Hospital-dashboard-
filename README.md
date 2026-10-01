# Hospital Emergency Room Dashboard

An interactive **Power BI dashboard** designed to analyze and monitor hospital emergency room operations. The project transforms raw emergency room data into a structured business intelligence report that helps users understand patient volume, admissions, waiting time, satisfaction, demographics, daily activity, and department referrals.

The dashboard presents the **July 2024** performance view and allows users to interact with the report using multiple filters and slicers.

---

## Project Overview

Emergency departments generate large amounts of operational data, including patient information, waiting times, admission status, referrals, and satisfaction scores. Reviewing this information directly from raw data can make it difficult to identify important patterns.

This project uses **Microsoft Power BI** to convert emergency room data into an interactive analytical dashboard.

The dashboard provides management and stakeholders with a centralized view of key emergency room metrics and enables them to explore different patient segments through interactive filtering.

### Key areas covered

- Patient volume
- Average waiting time
- Patient satisfaction
- Admission analysis
- Patient demographics
- Gender distribution
- Daily patient activity
- Department referrals
- Interactive patient filtering

---

## Business Objectives

The dashboard was developed to answer important operational questions such as:

- How many patients visited the emergency room?
- What was the average patient waiting time?
- What was the average patient satisfaction score?
- How many patients were admitted?
- Which age groups contributed the most patient visits?
- How were patients distributed by gender?
- What proportion of patients were admitted?
- Which departments received the highest number of referrals?
- How did patient volume change across different days?
- How do the results change when different patient filters are applied?

---

## Key Performance Indicators

| KPI | July 2024 |
|---|---:|
| No. of Patients | 9,210 |
| Average Wait Time | 35.26 |
| Average Satisfaction | 4.99 |
| Admitted Patients | 4,611 |

These KPIs provide a quick overview of emergency room performance for the selected period.

---

## Dashboard Analysis

### 1. Patient Demographics

The dashboard analyzes patients based on **age group and gender**.

This analysis helps identify the demographic composition of emergency room visitors and provides a better understanding of which patient segments contribute to overall patient demand.

---

### 2. Admission Analysis

The admission analysis compares patients based on their **admission status**.

It provides a quick overview of the relationship between total emergency room visits and patients who were admitted.

This can help users understand admission patterns and compare admitted versus non-admitted patients.

---

### 3. Daily Patient Trend

The daily patient trend displays patient activity across the selected period.

This helps identify variations in daily emergency room demand and provides useful information for operational planning and resource management.

---

### 4. Department Referral Analysis

The dashboard analyzes patient referrals across different hospital departments.

The report includes departments such as:

- General Practice
- Orthopedics
- Physiotherapy
- Cardiology
- Neurology
- Gastroenterology
- Renal

This analysis helps identify which departments receive the highest number of referrals from the emergency room.

---

### 5. Interactive Filtering

The dashboard includes interactive slicers that allow users to filter the analysis based on specific patient attributes.

Available filters include:

- Patient Race
- Department Referral
- Patient Admission Flag
- Patient Gender

Users can combine multiple filters to perform more focused analysis.

---

## Data Analytics Workflow

The project follows a structured Business Intelligence workflow:

```text
Raw Dataset
     ↓
Data Import
     ↓
Data Understanding
     ↓
Data Cleaning
     ↓
Data Transformation
     ↓
Data Modeling
     ↓
DAX Measures
     ↓
KPI Development
     ↓
Data Visualization
     ↓
Interactive Dashboard
     ↓
Business Insights
```

### Workflow Steps

1. Imported the emergency room dataset into Power BI.
2. Reviewed the structure and quality of the source data.
3. Cleaned and transformed the required fields using Power Query.
4. Prepared the dataset for analysis and visualization.
5. Created calculated measures using DAX.
6. Developed KPI cards for important operational metrics.
7. Created analytical visuals for demographics, admissions, trends, and referrals.
8. Added interactive slicers for user-driven analysis.
9. Designed a consistent dashboard layout focused on readability.
10. Validated the dashboard outputs and finalized the report.

---

## Tools & Technologies

| Tool / Technology | Purpose |
|---|---|
| **Microsoft Power BI** | Dashboard development and visualization |
| **Power Query** | Data cleaning and transformation |
| **DAX** | Calculated measures and KPIs |
| **Data Visualization** | Presenting analytical findings |
| **Business Intelligence** | Operational reporting and analysis |
| **Healthcare Data Analytics** | Emergency room performance analysis |

---

## Dashboard Preview

![image alt](https://github.com/mdh05804-bit/Hospital-dashboard-/blob/8ce6f7064d3a0072518dd683b1750951b58313ac/Screenshot_30-9-2026_231327_.jpeg)

> Place the dashboard screenshot in the repository root and name it `dashboard.png` to display the preview above.

---

## Repository Structure

```text
Hospital-Emergency-Room-Dashboard/
│
├── Hospital Emergency Room Dashboard.pbix
├── dashboard.png
├── README.md
│
└── dataset/
    └── hospital_emergency_room.csv
```

---

## How to Use the Project

### 1. Clone the Repository

Clone or download this repository to your local machine.

### 2. Open the Power BI File

Open:

```text
Hospital Emergency Room Dashboard.pbix
```

using **Power BI Desktop**.

### 3. Update the Dataset Path

If Power BI cannot locate the dataset, update the source path from:

**Transform Data → Data Source Settings**

and select the correct CSV file.

### 4. Refresh the Data

After connecting the dataset, refresh the report to load the latest available data.

### 5. Explore the Dashboard

Use the available slicers and visuals to analyze:

- Patient demographics
- Admission status
- Patient volume
- Waiting time
- Satisfaction
- Department referrals
- Daily patient activity

---

## Key Skills Demonstrated

This project demonstrates practical experience in:

- Data Cleaning
- Data Transformation
- Power Query
- DAX Measures
- KPI Development
- Data Visualization
- Interactive Dashboard Design
- Business Intelligence Reporting
- Healthcare Data Analysis
- Data Storytelling
- Insight Generation
- Dashboard Design

---

## Project Outcome

The final dashboard provides a centralized analytical view of emergency room activity.

Instead of relying on raw healthcare records, users can quickly monitor important operational metrics, compare patient segments, analyze admission patterns, identify referral trends, and understand changes in daily patient volume.

The project demonstrates how **Power BI can be used to transform raw operational data into an interactive business intelligence solution** that supports data-driven analysis and stakeholder communication.

---

## Portfolio Value

This project demonstrates the complete workflow of a practical **Data Analyst / Business Intelligence project**, including:

```text
Data → Cleaning → Transformation → Analysis → Visualization → Insights
```

It highlights the ability to work with real-world-style healthcare data and convert it into a structured dashboard suitable for operational reporting and portfolio presentation.

---

## Author

**Md Hasnain**

B.Tech — Mewar University  
Focus: **Data Analytics**

---

## Disclaimer

This project is created for **portfolio and learning purposes**. The dashboard demonstrates a practical approach to healthcare data analysis and business intelligence reporting.

The data and analysis should not be interpreted as medical advice or as an official representation of hospital operations.
