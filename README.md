# excel-data-cleaning-cafe-sales
Data cleaning, missing value handling, and structural standardization of 10,000 retail transactions using Excel

# ☕ Excel Data Cleaning & Audit Project: Café Sales Dataset

## 📌 Project Overview
This project demonstrates end-to-end data cleaning, anomaly detection, and data standardization on a raw retail dataset containing 10,000 transaction records.

## 🛠️ Data Issues Identified
- **Missing & Unknown Values:** Handled missing/unclear data points across key fields including `Item`, `Quantity`, `Price Per Unit`, `Total Spent`, `Payment Method`, and `Location`.
- **Data Type Mismatches:** Converted numerical values stored as string objects back into proper numeric data types.
- **Date Formatting:** Normalized transaction dates to standard YYYY-MM-DD formats.
- **Data Integrity:** Verified that `Total Spent` accurately matches `Quantity × Price Per Unit`.

## 📁 Repository Structure
- `cleaned_cafe_sales.xlsx`: Excel workbook containing raw data, cleaned output, and issue logging sheets.
- `dirty_cafe_sales.csv`: The Original Messy Excel workbook.

## 💡 Key Skills Demonstrated
- Data Cleaning & Preprocessing
- Error Logging & Anomaly Detection
- Data Quality Assurance & Validation
- Excel & Data Analysis
