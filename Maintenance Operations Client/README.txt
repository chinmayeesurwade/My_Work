# Maintenance Operations Client

## Operations Analytics & Reporting Automation Case Study

**Engagement:** Aug - Nov 2024\
**Role:** Business Analyst + Data Analyst\
**Primary Stakeholder:** Maintenance Manager\
**Client:** Confidential\
**Dataset:** Approximately 10,000 historical records across 20 teams\
**Core Tools:** Excel, Google Sheets, SQL, Python, Power Query, DAX,
Power BI

------------------------------------------------------------------------

## Project Overview

The Maintenance Operations Client engagement focused on improving
visibility and reducing manual effort in maintenance reporting.

Maintenance information was distributed across Excel, CSV, Google
Sheets, and database sources. The Maintenance Manager was manually
consolidating updates and had difficulty obtaining a consistent view of
work completion, overdue work, backlog, and performance across teams.

The project combined business analysis, data preparation, operational
analysis, KPI definition, and Power BI reporting. Approximately 10,000
historical records across 20 teams were cleansed and structured into a
consolidated analytical solution.

The resulting Power BI dashboard surfaced an overall **92% completion
rate** and removed approximately **3 to 4 hours of weekly manual
reporting effort**.

> **Important:** The 92% completion rate was an analytical finding
> surfaced by the dashboard. It is not presented as an improvement
> caused by the project.

## Business Problem

The existing reporting process created several operational challenges:

-   Maintenance updates required manual consolidation.
-   Management had limited visibility into overall work completion.
-   Overdue work orders and backlog were difficult to monitor
    consistently.
-   Team-level and technician-level performance required clearer
    reporting.
-   High-priority pending work needed better visibility.
-   Maintenance information came from multiple source formats and
    required standardization before reliable reporting.
-   Repetitive weekly reporting consumed approximately 3 to 4 hours of
    manual effort.

## Project Objectives

The project aimed to create a reliable maintenance reporting layer that
could:

-   consolidate fragmented maintenance information;
-   standardize inconsistent operational data;
-   establish consistent maintenance KPI definitions;
-   provide visibility into completed, open, pending, and overdue work;
-   analyze maintenance performance across teams and technicians;
-   identify backlog, workload imbalance, high-priority pending work,
    recurring maintenance categories, and equipment-related issues;
-   provide management with an interactive Power BI dashboard; and
-   reduce repetitive weekly reporting effort.

## Data Landscape

The analysis used approximately one year of historical operational
information represented by approximately 10,000 records across 20 teams.

Confirmed source types included:

-   Excel
-   CSV
-   Google Sheets
-   Database data

The records covered maintenance-related activity such as maintenance
tasks/work orders, inspections, service requests, and equipment-related
records.

Available analytical fields included:

-   Task / Work Order ID
-   Team
-   Technician
-   Asset / Equipment
-   Created Date
-   Due Date
-   Completion Date
-   Status
-   Priority
-   Category
-   Location
-   Remarks

## Data Quality Challenges

The source information was not analysis-ready. Confirmed data-quality
issues included:

-   duplicate records;
-   missing values;
-   inconsistent team names;
-   inconsistent date formats;
-   inconsistent status names; and
-   blank records.

The preparation workflow used Excel, Google Sheets, SQL, Python, and
Power Query as part of the overall analytical toolset.

## KPI & Operational Analysis

The solution analyzed operational performance through measures and
breakdowns including:

-   completed work orders;
-   open work orders;
-   pending tasks;
-   overdue work orders;
-   completion rate;
-   average completion time;
-   priority breakdown;
-   team-wise completion;
-   technician performance;
-   asset/equipment breakdown;
-   backlog;
-   workload imbalance;
-   high-priority pending work;
-   recurring maintenance categories; and
-   equipment-related issues.

### Completion Rate

**Completion Rate = Completed Maintenance Tasks / Total Assigned
Maintenance Tasks x 100**

The dashboard surfaced a **92% overall completion rate**.

### Overdue Rule

A maintenance item was treated as overdue using the confirmed business
rule:

**Due Date \< Current Date AND Status != Completed**

## Power BI Solution

A Power BI dashboard was built from scratch to provide the Maintenance
Manager with a consolidated operational view.

The exact historical page names and dashboard layout are not retained.
For the portfolio reconstruction, the reporting solution can be
organized logically around:

1.  Executive Maintenance Overview
2.  Work Order & Completion Analysis
3.  Team & Technician Performance
4.  Backlog, Priority & Asset Analysis

These page names represent a portfolio reconstruction and are not
claimed to be the exact historical dashboard structure.

## Confirmed Findings

The analysis surfaced operational visibility into:

-   a **92% overall completion rate**;
-   maintenance backlog;
-   overdue work;
-   differences in performance across teams;
-   workload imbalance;
-   high-priority pending work;
-   recurring maintenance categories; and
-   equipment-related issues.

Exact historical counts, percentages, team rankings, asset rankings, and
other detailed values are not retained and are therefore not reproduced
in this portfolio.

## Recommendations

Recommendations were provided to the Maintenance Manager and were
implemented.

The exact historical recommendations are not retained. This portfolio
therefore does **not** invent or attribute specific recommendations to
the original engagement.

Where proposed recommendations are included elsewhere in the case study,
they should be explicitly labeled as **portfolio-proposed
recommendations based on confirmed findings**, rather than historical
client recommendations.

## Delivery

Confirmed project delivery included:

-   Power BI dashboard;
-   live walkthrough;
-   presentation;
-   documentation; and
-   training.

## Business Impact

Two outcomes are retained and defensible:

**Operational visibility:** The dashboard surfaced an overall **92%
completion rate** and provided consolidated visibility into maintenance
performance.

**Reporting efficiency:** The solution eliminated approximately **3 to 4
hours of weekly manual reporting effort**.

The 3 to 4 hour figure should be described as reporting effort saved
without assigning the saving to a specific individual unless additional
evidence is available.

## End-to-End Project Flow

**Fragmented maintenance reporting -\> requirements and data discovery
-\> consolidation of approximately 10,000 historical records across 20
teams -\> data cleansing and standardization -\> maintenance
business-rule and KPI definition -\> operational analysis -\> Power BI
dashboard -\> management walkthrough and training -\> approximately 3 to
4 hours of weekly manual reporting effort eliminated**

## Repository Structure

``` text
Maintenance Operations Client/
|
|-- README.md
|
|-- 01_Project_Overview/
|   `-- Project Overview & Business Problem.docx
|
|-- 02_Requirements/
|   |-- Business Requirements Document (BRD).docx
|   `-- User Stories & Acceptance Criteria.docx
|
|-- 03_Data_Analysis/
|   |-- KPI Catalogue.docx
|   |-- Data Dictionary.docx
|   `-- Data Cleaning & Preparation Methodology.docx
|
|-- 04_Operational_Analysis/
|   |-- Maintenance Performance Analysis.docx
|   `-- Backlog & Overdue Work Order Analysis.docx
|
|-- 05_Solution/
|   |-- Power BI Requirements.docx
|   `-- Data Model & DAX Measures.docx
|
|-- 06_Dashboard/
|   |-- Executive Maintenance Overview.png
|   |-- Work Order & Completion Analysis.png
|   |-- Team & Technician Performance.png
|   `-- Backlog, Priority & Asset Analysis.png
|
|-- 07_Insights/
|   `-- Findings & Recommendations.docx
|
|-- 08_Testing/
|   `-- Data Validation & Dashboard Testing.docx
|
`-- 09_Final_Report/
    `-- End-to-End Project Report.docx
```

## Skills Demonstrated

### Business Analysis

Requirements discovery, stakeholder communication, operational problem
framing, KPI definition, business-rule definition, root-cause thinking,
findings-to-action translation, documentation, walkthrough, and user
training.

### Data Analysis & BI

Data cleansing, data standardization, SQL, Python, Power Query, DAX,
Power BI, operational KPI analysis, work-order analysis, backlog and
overdue analysis, team/technician performance analysis, and reporting
automation.


------------------------------------------------------------------------


