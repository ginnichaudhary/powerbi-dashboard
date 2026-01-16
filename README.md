# ONEST Job Seeker Data Analysis & Power BI Dashboard

## Project Overview
This project was completed as part of the ONEST Data Associate / Data Intern Assignment.  
The objective of the project is to convert unstructured job seeker data into a clean, structured format, derive meaningful insights, and visualise those insights using a Power BI dashboard.

ONEST focuses on building population-scale digital public infrastructure to improve job discovery and hiring efficiency. This project supports that vision by strengthening the data backbone required for pilot execution and analytics.

---

## Assignment Objectives
The project addresses the following objectives:

1. Convert unstructured raw datasets into a structured processed dataset as per the given template  
2. Apply data quality checks and clearly state assumptions  
3. Identify and document key insights from the processed data  
4. Visualise insights using a BI tool (Power BI)  
5. Share outputs in an easy-to-review and reusable format  

---

## Dataset Description

### Raw Data
- Two separate raw datasets containing job seeker information  
- Data contained inconsistencies, missing values, and varied formats  

### Processed Data
- All raw datasets were consolidated into a single structured template  
- Each row represents one job seeker record  
- Columns were standardised for consistency and bulk upload readiness  

---

## Data Cleaning & Processing

The following steps were applied:

- Merged multiple raw datasets into one unified dataset  
- Standardised column names (Name, Phone, Institution, Course, Branch, etc.)  
- Removed duplicate records using phone number as a primary identifier  
- Cleaned invalid or incomplete contact details  
- Retained missing values as blank where data was unavailable  
- Avoided fabricating or guessing missing information  

### Assumptions
- Missing fields in raw data were left blank in the processed dataset  
- Invalid phone numbers were removed to ensure reliable communication  
- Institute-related address information was treated as permanent address where applicable  
- Data from different sources was merged without altering original intent  

---

## Key Insights
The processed dataset enables the following insights:

- Total number of job seekers onboarded  
- Institution-wise distribution of job seekers  
- Course-wise and branch-wise distribution  
- Availability of contact details (phone/email)  
- Cross-analysis of courses across institutions  
- Overall data completeness and quality indicators  

---

## Power BI Dashboard

A one-page Power BI dashboard was created to visualise the above insights in a clear and interactive manner.

### Dashboard Features
- Total Job Seekers (overall count)  
- Institution-wise Job Seeker distribution  
- Course-wise Job Seeker distribution  
- Branch-wise distribution  
- Contact information availability indicators  
- Detailed tabular view of job seeker records  

The dashboard is designed to be simple, clean, and aligned with operational decision-making needs.

---

## Repository Structure

onest-powerbi-dashboard/
|
|-- ONEST_JobSeeker_Dashboard.pbix
|-- dashboard_screenshot.png
|-- ONEST_Dashboard.pdf
|-- One_Pager_Insights.docx
|-- README.md

---

## How to View the Dashboard

### Option 1: Power BI Desktop
1. Download the file `ONEST_JobSeeker_Dashboard.pbix`  
2. Open it using Power BI Desktop  

### Option 2: PDF View
- Open `ONEST_Dashboard.pdf` for a static view of the dashboard  

---

## Tools Used
- Power BI Desktop  
- Microsoft Excel / Google Sheets  
- GitHub  

---

## Key Takeaways
- Hands-on experience with messy, real-world data  
- Strong focus on data quality and integrity  
- Practical application of BI tools for insight generation  
- Clear alignment with ONEST’s operational goals  

---

## Author
Ginni Chaudhary  
Aspiring Data Analyst / Data Associate  

---

This repository contains all required deliverables for the ONEST assignment and is ready for evaluation.
