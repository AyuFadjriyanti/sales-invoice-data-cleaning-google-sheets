
# Data Entry & Data Cleaning Portfolio Project

## Sales & Invoice Dataset

This project demonstrates a Data Entry & Data Cleaning workflow using a sales and invoice dataset.
The main focus of this project is to show how raw, messy data from manual input can be cleaned, standardized, and prepared for analysis.

## 📌 Project Overview

The goal of this project is to practice and demonstrate:

✅ Manual data entry handling

✅ Identifying common data errors

✅ Cleaning and standardizing data

✅ Documenting the cleaning process

✅ Creating a clean, analysis-ready dataset

## 🏢 Business Context

A retail company records sales and invoice data manually.
Because of manual data entry, the dataset contains:
- Duplicate records
- Inconsistent text values
- Incorrect date formats
- Missing or invalid numbers
- The company needs clean and reliable data for reporting and analysis.

## 📂 Dataset Information

- Data type: Sales & Invoice
- Total records (before cleaning): 1000 rows
- File format: Excel
- Time period: January – June 2024

### Dataset Columns
- invoice_id
- invoice_date
- customer_name
- customer_type
- product_name
- category
- qty
- unit_price
- total_amount
- payment_status
- city
- sales_channel

## 📁 Project Structure

📦 data-entry-cleaning-project

│

├── 📊 sales_invoice_dummy_1000_rows.xlsx

│   ├── raw_data        # before cleaning

│   ├── cleaning_process_log  # steps & notes

│   ├── cleans_data      # after cleaning

│   └── before_after_summary  # comparison

│

└── 📄 README.md


## 🚧 Data Problems Found (Before Cleaning)

The raw dataset contains common data entry issues such as:
- Duplicate invoice IDs
- Inconsistent date formats
- Typos in customer type and city names
- Extra spaces in text fields
- Quantity values are missing or equal to zero
- Inconsistent payment status values

## 🧹 Data Cleaning Process

The following steps were performed during data cleaning:
- Removed duplicate records
- Standardized date formats
- Cleaned text values (trim spaces, consistent casing)
- Standardized categorical values
- Filled missing or invalid quantity values
- Validated data using Excel Data Validation
- Identify payment conditions using Conditional Formatting
- Rechecked total_amount calculations
All steps are documented in the cleaning_process_log sheet.

## 🔍 Before vs After Summary

| Metric | Before Cleaning | After Cleaning |
|--------|-----------------|----------------|
| Total Records |1000 | 616 |
| Duplicate Data | Yes | No |
| Inconsistent Text | Yes | No |
| Missing Values | Yes | No |
| Data Ready for Analysis | ❌ | ✅ |


## 🛠️ Tools Used

- Microsoft Excel / Google Sheets
- Data Validation
- Basic Excel Functions
- Filters & Tables
- Conditional Formatting

## 🎯 Skills Demonstrated

- Data Entry Handling
- Data Cleaning & Standardization
- Attention to Detail
- Data Validation
- Documentation of Work

## 📈 Project Outcome

After cleaning:
- The dataset became structured and consistent
- Errors caused by manual input were removed
- The data is now ready for:
    - Analysis
    - Dashboard creation
    - Business reporting
