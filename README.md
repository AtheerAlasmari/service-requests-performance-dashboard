
# Service Requests Performance Dashboard

### Power BI | Power Query | DAX | Data Analytics | Business Intelligence

An interactive Power BI dashboard designed to analyze service request performance, monitor operational efficiency, and evaluate compliance with Service Level Agreements (SLAs).

The project transforms operational data into meaningful insights to support performance monitoring and data-driven decision-making.

---

## 1. Project Overview

This project focuses on analyzing service requests across different regions and service categories.

The dashboard provides two interactive reporting pages:

- **Executive Overview:** A high-level view of service volumes, request statuses, and regional performance.
- **Operational Analysis:** A detailed evaluation of resolution times, service efficiency, and SLA compliance.

## 2. Business Problem

Organizations often face challenges in monitoring service delivery when operational information is distributed across multiple reports.

Without centralized reporting, it becomes difficult to:

- Track service request volumes and completion rates.
- Identify regions with high service demand.
- Monitor request processing times.
- Evaluate compliance with target resolution durations.
- Identify potential operational bottlenecks.

**Project Objective:** Develop an interactive business intelligence solution that consolidates operational KPIs and enables stakeholders to monitor service performance effectively.

---

## 3. Key Performance Indicators (KPIs)

| KPI | Result |
|---|---:|
| Total Requests | 1,200 |
| Completed Requests | 980 |
| In-Progress Requests | 133 |
| Cancelled Requests | 87 |
| Completion Rate | 81.67% |
| SLA Compliance Rate | 83.57% |
| Average Resolution Time | 3.9 Days |
| Completed Requests Exceeding Target Duration | 161 |

### KPI Definitions

- **Completion Rate:** Percentage of total requests successfully completed.
- **SLA Compliance Rate:** Percentage of completed requests resolved within their target duration.
- **Average Resolution Time:** Average number of days required to resolve completed requests.
- **Exceeded Target Duration:** Number of completed requests that took longer than their assigned target duration.

---

## 4. Dashboard Pages

### Page 1: Executive Overview

Provides a consolidated view of overall service request activity.

**Key Features:**
- Executive KPI cards.
- Monthly Requests Trend.
- Requests Status Distribution.
- Requests by Region.
- Requests by Service Type.

**Dashboard Preview:**

![Executive Overview](Executive-Overview.png)

### Page 2: Operational Analysis

Focuses on service efficiency and resolution performance.

**Key Features:**
- Average Resolution Time KPI.
- SLA Compliance KPI.
- Actual vs. Target Duration.
- Average Duration by Region.
- Average Duration by Service Type.
- Monthly Resolution Trend.

**Dashboard Preview:**

![Operational Analysis](Operational-Analysis.png)

---

## 5. Data Preparation & Analysis

Data preparation and transformation were performed using **Power Query**, while analytical measures were developed using **DAX**.

### Data Preparation
- Reviewed the dataset structure and column data types.
- Cleaned and transformed operational data.
- Validated data quality and handled missing values.
- Prepared date, region, status, and service category fields for analysis.

### Data Analysis
- Calculated key performance indicators using DAX.
- Analyzed request volumes and status distributions.
- Evaluated regional and service-level performance.
- Compared actual resolution durations against target durations.
- Measured SLA compliance and identified requests exceeding their targets.

---

## 6. Key Findings

The analysis identified several important operational performance indicators:

- **81.67% Completion Rate:** 980 out of 1,200 service requests were completed.
- **83.57% SLA Compliance:** Most completed requests met their assigned target resolution duration.
- **161 Exceeded Requests:** A portion of completed requests exceeded their target resolution duration.
- **3.9 Days Average Resolution Time:** Completed requests required an average of approximately 3.9 days to resolve.
- **Regional Demand Differences:** Request volumes varied across regions, highlighting differences in operational demand.

These findings provide a foundation for evaluating service efficiency and identifying areas requiring further investigation.

## 7. Business Recommendations

Based on the dashboard findings, the following actions are recommended:

1. **Improve SLA Compliance:** Investigate the causes of requests exceeding their target resolution durations.
2. **Monitor High-Demand Regions:** Review workload distribution and resource allocation across regions.
3. **Analyze Service Delays:** Identify service categories associated with longer resolution times.
4. **Track Operational KPIs:** Establish regular monitoring of completion rates, average resolution times, and SLA compliance.
5. **Support Continuous Improvement:** Use dashboard insights to prioritize operational improvements and evaluate their effectiveness.

---

## 8. Interactive Dashboard Features

The Power BI report supports interactive analysis through:

- Cross-visual filtering and interactions.
- Region-based performance exploration.
- Service category comparisons.
- Dynamic KPI updates based on report selections.

These capabilities allow users to explore performance patterns and investigate operational results.

---

## 9. Tools & Skills Demonstrated

| Tool / Skill | Application |
|---|---|
| Power BI | Interactive dashboard development |
| Power Query | Data cleaning and transformation |
| DAX | KPI calculations and analytical measures |
| Data Analysis | Operational performance evaluation |
| Data Visualization | Visual presentation of performance trends |
| Business Intelligence | Decision-support reporting |
| SLA Analysis | Target duration and compliance monitoring |

---

## 10. Business Value

The dashboard provides a centralized view of service operations, enabling stakeholders to:

- Monitor operational performance.
- Evaluate service delivery efficiency.
- Identify potential service bottlenecks.
- Track compliance with target service levels.
- Support data-driven operational decisions.

The project demonstrates the application of business intelligence techniques to transform operational data into actionable insights.

---

## 11. Project Documentation

[View Project Documentation (PDF)](Service%20Requests%20Performance%20Dashboard.pdf)

---

**Project Type:** Data Analytics Portfolio Project  
**Primary Tool:** Microsoft Power BI  
**Developed By:** Atheer Alasmari

