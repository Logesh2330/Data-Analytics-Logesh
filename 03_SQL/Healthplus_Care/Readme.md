# 🏥 HealthPlus Care – Healthcare Analytics

## 📌 Project Overview

HealthPlus Care is a **SQL/MySQL Healthcare Analytics Project** designed to analyze healthcare service utilization, financial performance, member engagement, and patient experience.

The project uses cleaned and validated healthcare datasets to generate meaningful business insights and key performance indicators (KPIs) that support data-driven decision-making.

## 🎯 Project Objectives

- Analyze member registrations and consultation activities.
- Measure telemedicine utilization and completion rates.
- Evaluate chronic care programs and health package subscriptions.
- Analyze prescriptions, laboratory tests, and insurance claims.
- Monitor billing, payments, and collection performance.
- Evaluate member feedback and healthcare workforce operations.

## 🛠️ Technology Stack

- **Database:** MySQL
- **Query Language:** SQL
- **Data Source:** CSV Files
- **Tools:** MySQL Workbench / phpMyAdmin

## 🗄️ Database Information

**Database Name:** `healthplus_care_db`

The database contains **17 tables** covering members, clinics, specialists, consultations, telemedicine, chronic care programs, health packages, prescriptions, laboratory tests, insurance claims, billing, payments, staff, corporate members, and feedback.

## 📊 Dataset Summary

| Dataset Category      | Records |
| --------------------- | ------: |
| Members               |   2,500 |
| Consultations         |   6,000 |
| Telemedicine Sessions |   2,200 |
| Chronic Care Programs |     900 |
| Package Subscriptions |   3,000 |
| Prescriptions         |   5,000 |
| Laboratory Tests      |   3,500 |
| Insurance Claims      |   1,800 |
| Billing Records       |   6,000 |
| Payment Records       |   6,000 |
| Member Feedback       |   2,500 |

## 📈 Key Performance Indicators (KPIs)

- Total Members
- Total Consultations
- Consultation Completion Rate
- Telemedicine Completion Rate
- Active Chronic Care Programs
- Package Subscription Rate
- Total Insurance Claim Amount
- Total Billed Amount
- Net Collection Amount
- Collection Gap
- Average Member Feedback Rating
- Total Staff and Specialists

## 🔄 Project Workflow

1. Import CSV datasets.
2. Create the MySQL database and tables.
3. Perform data cleaning and standardization.
4. Validate data quality and relationships.
5. Execute SQL business analysis queries.
6. Calculate healthcare and financial KPIs.
7. Generate business insights for reporting and dashboards.

## 💻 SQL Concepts Used

- Aggregate Functions: `count()`, `sum()`, `avg()`
- Grouping and Filtering: `group by`, `having`
- Joins: `inner join`, `left join`, `right join`
- Common Table Expressions (CTEs)
- Window Functions: `row_number()`, `rank()`, `lag()`, `lead()`
- Data Cleaning and Validation
- Business KPI Calculations
- Financial Reconciliation and Duplicate-Counting Prevention

## 💰 Financial Analysis

Billing and payment transactions are analyzed separately where necessary to prevent double-counting caused by one-to-many relationships. This approach helps improve the reliability of billed amounts, collections, and outstanding balance analysis.

## 💡 Business Value

This project demonstrates how SQL can transform raw healthcare data into structured information for:

- Healthcare service performance monitoring
- Member engagement analysis
- Financial and collection tracking
- Insurance claim analysis
- Operational performance evaluation
- Data-driven healthcare decision-making

## ✅ Project Outcome

HealthPlus Care demonstrates practical SQL skills in database management, data cleaning, data validation, relational joins, advanced analytical queries, and KPI development. The resulting insights can be used as a foundation for healthcare analytics reports and dashboards.

**Project Type:** Academic / Data Analytics Project
**Domain:** Healthcare Analytics
**Database:** MySQL
**Language:** SQL
