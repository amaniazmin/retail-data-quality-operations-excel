# Retail Data Quality & Operations Control

## Project Overview

An Excel-based retail data operations workflow developed using a real-world retail transaction dataset.

The workflow validates, investigates, reconciles, and prepares transaction data before downstream processing.

---

## Business Workflow

Retailer Input File

↓

Raw Data Validation

↓

Exception Detection

↓

Exception Management

↓

Clean Output Generation

↓

Operational Dashboard

↓

Downstream Delivery

---

## Dataset

- Source: UCI Machine Learning Repository
- Dataset: Online Retail II
- Transactions analyzed: 9,999

---

## Validation Rules

- Customer ID validation
- Cancellation detection
- Quantity validation
- Price validation
- Duplicate detection

---

## Exception Management

Transactions were classified into:

- PASS
- REVIEW
- REJECT

---

## Results

| KPI | Value |
| --- | ---: |
| Total Records | 9,999 |
| PASS | 6,705 |
| REVIEW | 489 |
| REJECT | 2,805 |
| Pass Rate | 67.10% |
| Exception Rate | 32.90% |

---

## Skills Demonstrated

- Microsoft Excel
- Data Validation
- Data Quality
- Exception Management
- Data Cleansing
- Duplicate Detection
- IF Statements
- COUNTIF
- Pivot Tables
- Dashboard Development
- Operational Reporting

---

## Excel Workbook

[📊 Download the workbook](./excel/retail_data_operations_control.xlsx)

---

## Validation Workflow

![](./screenshots/validation-workflow.png)

---

## Exception Queue

![](./screenshots/exception-queue.png)

---

## Control Dashboard

![](./screenshots/control-dashboard.png)
