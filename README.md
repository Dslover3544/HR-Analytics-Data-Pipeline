# HR Analytics Data Pipeline

## Overview

This project simulates a real-world HR Analytics and Data Engineering workflow. The pipeline ingests employee data, performs data quality validation, generates workforce metrics, and produces reporting-ready datasets for business intelligence dashboards.

## Business Problem

HR teams often receive employee data from multiple systems that contain missing values, duplicate records, and inconsistent formatting. This project automates data cleaning and validation to improve reporting accuracy and workforce analysis.

## Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook / Google Colab
- CSV Data Processing
- Data Quality Validation
- GitHub

## Project Workflow

Raw Employee Data

↓

Data Cleaning

↓

Data Validation

↓

Business Metrics Generation

↓

Dashboard-Ready Outputs

## Data Quality Checks

The pipeline validates:

- Missing employee IDs
- Duplicate records
- Missing departments
- Invalid salary values
- Date formatting issues

## Key Metrics Generated

- Employee headcount by department
- Average salary by department
- Attrition counts
- Attrition rates
- Workforce distribution

## Output Files

### clean_employee_data.csv

Cleaned employee dataset ready for analysis.

### data_quality_report.csv

Summary of data quality issues identified.

### hr_summary_metrics.csv

Department-level workforce metrics and attrition analysis.

## Sample Business Insights

- IT has the highest average salary.
- Finance shows elevated attrition compared to HR.
- Operations contains the largest workforce segment.
- Data quality validation identifies missing and invalid records before reporting.

## Future Enhancements

- PostgreSQL integration
- Automated ETL scheduling
- Power BI dashboards
- Star schema dimensional modeling
- Microsoft Fabric implementation

## Author

Teni Gbolahan
B.S. Data Science
