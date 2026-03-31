# PwC Digital Assurance – Data Analysis & IT Audit

## Overview
This project is based on the PwC Switzerland Digital Assurance Virtual Experience, focusing on both data analysis and IT audit procedures. The project combines financial data analysis with ERP user authorization review to identify potential risks and control weaknesses.

## Objective
To analyze claim payment data and evaluate IT access controls in order to identify anomalies, assess risks, and provide actionable recommendations.

## Tools & Technologies
- Microsoft Excel (Pivot Tables, Data Analysis, Dashboarding)
- Data Visualization (Charts & KPI dashboards)
- Audit Framework (IT General Controls – ITGC)

## Part 1: Data Analysis

### Key Analysis Performed
- Analysis of claim payments across multiple years
- Identification of trends and anomalies in payment data
- Creation of dashboards using pivot tables and charts

### Key Insights
- Claim activity increased significantly between 2016 and 2018
- Multiple claims were processed with a consistent value of ~4,999 CHF
- Payment pattern suggests transactions may be structured below approval thresholds
- Increase in total payments driven by higher claim frequency, not value per claim

---

## Part 2: IT Authorization Audit

### Scope
- Joiners (new user access)
- Movers (role changes)
- Leavers (access removal)
- Password configuration review

### Key Findings
- One instance of incorrect role assignment identified (control weakness)
- Role changes and user deactivation processes were generally compliant
- Password parameters aligned with policy requirements

---

## Risk Assessment
- Overall Risk Level: Medium
- Risk driven by:
  - Repetitive payment patterns near approval thresholds
  - Identified role assignment control weakness

---

## Recommendations
- Strengthen role assignment and approval controls
- Monitor repetitive claim patterns for potential threshold avoidance
- Implement periodic access reviews for user roles
- Enhance automated controls for authorization management

---

## Deliverables
- Excel dashboard analyzing claim data
- IT audit testing tables (Joiners, Movers, Leavers, Password parameters)
- PowerPoint presentation summarizing findings
