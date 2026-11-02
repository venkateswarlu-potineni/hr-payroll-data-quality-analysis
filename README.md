# HR & Payroll Data Quality Analysis

## Project Overview

This project focuses on identifying data quality issues in employee and payroll datasets using Oracle SQL and Microsoft Excel.

I analyzed 1,000 employee records and 1,000 payroll records to identify missing information, duplicate employee IDs, invalid salary values, and payroll calculation discrepancies.

## Tools Used

- Oracle Database 21c
- Oracle SQL Developer
- Microsoft Excel
- SQL

## Data Quality Checks Performed

1. Identified duplicate employee IDs.
2. Checked for missing employee information.
3. Identified invalid salary values.
4. Compared recorded net pay with calculated net pay.
5. Identified payroll records with unmatched employee IDs.
6. Checked for missing employee IDs in payroll records.

## Key Findings

| Data Quality Check | Result |
|---|---:|
| Employee Records | 1,000 |
| Payroll Records | 1,000 |
| Repeated Employee IDs | 1 |
| Employee Records with Missing Information | 5 |
| Invalid Employee Salaries | 3 |
| Payroll Calculation Discrepancies | 4 |
| Unmatched Payroll Employee IDs | 3 |
| Missing Payroll Employee IDs | 0 |

The duplicate count represents the number of repeated employee IDs, while the other issue counts represent affected records. Some issues may overlap.

## Excel Dashboard

I created an Excel dashboard containing:

- Employee and payroll record KPI cards
- Data quality issues bar chart
- Key findings
- Project summary

## Project Structure

```text
HR_Payroll_Project/
├── data/
│   ├── employees_raw.csv
│   └── payroll_raw.csv
├── sql/
│   └── hr_payroll_data_quality_summary.sql
├── reports/
│   ├── hr_payroll_data_quality_summary.csv
│   └── hr_payroll_data_quality_summary.xlsx
└── README.md
```

## Project Outcome

This project helped me practice SQL data validation, aggregate queries, joins, payroll reconciliation, and Excel dashboard creation.

The analysis identified data quality issues that could affect HR reporting and payroll accuracy.

**Note:** This project uses synthetic practice datasets, not actual employee or company payroll records.