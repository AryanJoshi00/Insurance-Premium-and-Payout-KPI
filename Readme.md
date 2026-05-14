# Insurance Premium and Payout KPI Dashboard

A Power BI dashboard built to analyze insurance policy data across key operational and financial metrics. Designed to support business visibility into premium collection, policy distribution, agent performance, and payout trends.

## Dashboard Overview

The dashboard tracks 9,945 policies with KPI cards for Total Annual Premium (887M), Total Premium Amount (16.14bn), Total Premium Paid (3.69bn), Total Premium Payable (12.46bn), and Underwriting Expenses (52.70M).

## Visuals Included

- Total Annual Premium by Policy Type (Whole, Endowment, Universal)
- Total Annual Premium by Policy Name
- Total Annual Premium by Sales Agent
- Total Annual Premium by State
- Total Annual Premium by Occupation
- Premium Amount by Year (2016 to 2024)

## Filters

Policy Type, Policy Name, Sales Agent, Gender, Occupation, Year

## Data Model

| Table | Description |
|---|---|
| FCT.Insurance_Policy_Table | Core fact table with policy and premium records |
| DM.Customer_Detail_Table | Customer demographics |
| DM.Insurance_Agent_Table | Agent information |
| DM.Policy_Protection_Plan | Policy plan details |
| DM.Policy_Type | Policy type dimension |
| DM.Regional_Manager | Regional manager mapping |
| DM.Zonal_Manager | Zonal manager mapping |

## Tools

Power BI Desktop, Microsoft Excel

## Preview

![Dashboard](dashboard.png)