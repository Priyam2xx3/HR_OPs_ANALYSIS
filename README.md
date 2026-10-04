# HR Operations Analytics

This project analyzes employee attrition using the IBM HR Analytics dataset. The goal is to understand why employees leave, which teams and roles are most affected, and what changes can improve retention.

## Overview

The analysis combines:
- Excel for pivot tables, KPIs, and dashboard visuals
- MySQL for SQL-based attrition analysis
- Business-analyst reporting to translate findings into recommendations

## Business Question

The project focuses on questions such as:
- Which departments and job roles experience the highest attrition?
- Which age and tenure groups are at the greatest risk?
- Which retention strategies would be most effective?

## Dataset

- Source: IBM HR Analytics Employee Attrition dataset
- File: `data/hr_attrition_raw.csv`

## Project Structure

- `data/` – raw dataset
- `excel/` – analysis files and dashboard
- `docs/` – business report
- `sql/` – MySQL queries

## Key Insights

- Sales and HR departments show higher attrition than R&D
- Sales Representative and Laboratory Technician roles are high-risk
- Attrition is highest among younger employees and those in the first few years of employment
- Senior roles show comparatively lower attrition

## Tools Used

- Excel
- MySQL / SQL
- GitHub
- Business analysis and reporting

## How to Use

1. Open the dashboard in the `excel/` folder.
2. Import the raw CSV into MySQL as a table named `employees`.
3. Run the queries in `sql/hr_attrition_mysql.sql`.
4. Review the findings in `docs/ba_report.md`.

## Business Report

The detailed analysis and recommendations are available in [docs/ba_report.md](docs/ba_report.md).

