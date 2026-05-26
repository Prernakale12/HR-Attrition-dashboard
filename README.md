# HR Attrition & Workforce Insights Dashboard
### Google Sheets + Power BI | People Analytics Project

## Overview
An end-to-end HR analytics project built on the IBM HR Employee Attrition dataset
(1,470 employees). Analyses workforce attrition trends using Google Sheets (data
cleaning, Pivot Tables) and a 3-page interactive Power BI
dashboard with 8 DAX measures.

## Business Questions Answered
- What is the overall attrition rate?
- Which departments and job roles have the highest attrition risk?
- Does salary level predict whether an employee will leave?
- How does job satisfaction correlate with attrition?
- Does overtime significantly increase attrition?

## Key Findings
| Insight | Finding |
|---------|---------|
| Overall Attrition Rate | 16.1% (237 of 1,470 employees) |
| Highest Risk Role | Sales Representatives (~40% attrition) |
| Overtime Impact | Overtime employees leave at 3x the rate |
| Salary Gap | Leavers earn ~$2,000/month less than stayers |
| Satisfaction Link | Score 1 employees leave at 2x rate of Score 4 |
| Peak Attrition Tenure | Years 1-2 at the company |

## Dashboard Screenshots

### Page 1 — Executive Overview
![Overview](https://github.com/Prernakale12/HR-Attrition-dashboard/blob/main/Screenshots/Page1%20Overview.png)

### Page 2 — Attrition Deep Dive
![Deep Dive](https://github.com/Prernakale12/HR-Attrition-dashboard/blob/main/Screenshots/Page2%20Deep%20dive.png)

### Page 3 — Department & Role View
![Department View](https://github.com/Prernakale12/HR-Attrition-dashboard/blob/main/Screenshots/Page3%20Department.png)

## Tech Stack
| Tool | Purpose |
|------|---------|
| Google Sheets | Data cleaning, calculated columns, Pivot Tables |
| Power BI DAX | 8 KPI measures, attrition rate, income analysis |
| Power BI Report | 3-page interactive dashboard |
| GitHub | Version control & project sharing |

## How to Use
1. Download the IBM HR dataset from Kaggle (link below)
2. Open the Google Sheet link to view analysis (https://docs.google.com/spreadsheets/d/1PrkRQ11cWnreW9cg_0qjfXkLiL2o7j-M27KZJg6ZANk/edit?usp=sharing)
3. Download `powerbi/HR_Attrition_Dashboard.pbix` and open in Power BI Desktop (free)
4. Use slicers to filter by Department, Gender, or OverTime status

## Dataset
[IBM HR Analytics Employee Attrition](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
