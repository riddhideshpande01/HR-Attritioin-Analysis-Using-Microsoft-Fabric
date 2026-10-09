# HR-Attritioin-Analysis-Using-Microsoft-Fabric

## 1. Project Overview

An end-to-end HR Analytics solution built using Microsoft Fabric to analyze employee attrition and understand the factors influencing employee turnover. The project uses a dataset of 1,470 employee records to explore attrition patterns across departments, salary bands, and age groups.

The goal is to transform raw HR data into meaningful insights that help HR teams understand why employees leave, identify departments experiencing higher attrition, and make informed employee retention decisions.

## 2. Project Objectives

- Analyze the overall employee attrition rate.
- Identify departments experiencing the highest employee attrition.
- Examine the relationship between salary, age, and employee attrition.
- Identify workforce segments that may require targeted retention strategies.
- Implement secure, department-level access to employee analytics.
- Protect confidential employee information using sensitivity labels.

## 3. Tech Stack

- **Microsoft Fabric:** End-to-end data analytics and data integration platform.
- **Dataflow Gen2:** Data ingestion and preparation.
- **Power BI:** Interactive HR analytics dashboards and visual reporting.
- **DAX:** Calculated measures, calculated columns and dynamic row-level security logic.
- **Column level Security:** Hides employees data for example: Monthly income
- **Sensitivity Labels:** Help protect confidential employee data.

## 4. Data Source

**Dataset:** IBM HR Employee Attrition Dataset

**Total Records:** 1,470 employee records

The dataset contains employee-related information used to analyze workforce characteristics and attrition patterns.

Key analytical dimensions include:

- **Department:** Compare attrition across different departments.
- **Salary:** Examine whether attrition patterns vary across salary levels.
- **Age:** Analyze attrition across different age groups.
- **Employee Attrition:** Identify employees who have left and calculate attrition metrics.


## 5. Features and Highlights

### A. End-to-End Data Integration

- Ingested 1,470 employee records into Microsoft Fabric using Dataflow Gen2.
- Prepared HR data for analysis and reporting.
- Built an integrated workflow to support employee attrition analysis.

### B. Employee Attrition Analysis

- **Overall Attrition Rate:** Evaluates the proportion of employees who have left the organization.
- **Department-Wise Attrition:** Identifies departments with comparatively higher employee exits.
- **Salary-Based Analysis:** Examines attrition patterns across salary bands.
- **Age-Based Analysis:** Compares employee turnover across age groups.
- **Attrition Drivers:** Explores relationships between salary, age, department, and the decision to leave.

### D. Data Confidentiality

Applied sensitivity labels to help classify and protect confidential employee information, supporting responsible handling of HR data.

### E. Business-Focused Insights

The analysis helps HR teams:

- Understand employee turnover patterns.
- Identify departments with higher attrition.
- Explore salary and age-related differences in attrition.
- Recognize workforce segments that may need further investigation.
- Prioritize data-informed employee retention strategies.

## 6. Business Questions Answered

This project addresses the following HR business questions:

1. Why are employees leaving the company?
2. What is the overall employee attrition rate?
3. Which departments are losing the most employees?
4. Is there a relationship between salary, age, and the decision to leave?

## 7. Key Learning Outcomes

- Gained practical experience with Microsoft Fabric and Dataflow Gen2.
- Applied HR analytics concepts to explore employee attrition.
- Used DAX and column-level security.
- Learned to implement department-level data access controls.
- Applied sensitivity labels to support data confidentiality.
- Connected technical data processing with practical HR business questions.

## 8. Business Impact

The solution provides a structured view of employee attrition across departments, salary bands, and age groups. By highlighting turnover patterns and potential attrition drivers, it supports HR teams in identifying areas for further investigation and developing more focused employee retention strategies.

## 9. Future Enhancements

- Add predictive analytics to estimate employee attrition risk.
- Incorporate additional factors such as job satisfaction, overtime, and years at the company, if available.
- Develop automated reporting and scheduled data refresh.
- Track attrition trends over time.
- Extend the dashboard with actionable retention recommendations.

## 10. Conclusion

This project demonstrates how Microsoft Fabric can support end-to-end HR analytics by combining data ingestion, employee attrition analysis, reporting, and security controls. It transforms employee data into business-focused insights that can help HR teams better understand workforce turnover and support informed decision-making.

**Project Domain:** Human Resources Analytics
**Focus Areas:** Employee Attrition | Workforce Analytics | Data Integration | Business Intelligence | Data Security

**Screen Shots** <br>                                                                                                                                        Overview: https://github.com/riddhideshpande01/HR-Attritioin-Analysis-Using-Microsoft-Fabric/blob/main/dashboardScreenshot/Overview.png  <br>                        Deep dive: https://github.com/riddhideshpande01/HR-Attritioin-Analysis-Using-Microsoft-Fabric/blob/main/dashboardScreenshot/deepDive.png
