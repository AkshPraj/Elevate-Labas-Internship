# 🧹 Sales Data Cleaning Project

### 📌 Objective

To clean and prepare a raw sales dataset by handling missing values, duplicates, inconsistent text formats, and incorrect data types. The cleaned dataset will be used for downstream analysis or reporting.

### 🧰 Tools Used

- Python (Pandas)
- Jupyter Notebook / Google Colab
- OR Excel for non-programmatic data cleaning

## 📝 Cleaning Steps Performed

## Task	Description

- 🔍 Missing Values	Identified using .isnull() and handled by imputation or row removal.
- ♻️ Duplicates	Removed using .drop_duplicates() or Excel's "Remove Duplicates".
- 🧑‍💼 Standardized Text	Gender, country names, etc., were cleaned for consistency (e.g., male, Male, MALE → Male).
- 📆 Date Format Fixes	Converted all dates to consistent format (DD-MM-YYYY).
- 🏷️ Column Name Cleanup	Renamed headers to lowercase with underscores (e.g., Order Date → order_date).
- 🔢 Data Type Corrections	Ensured numeric fields (like age, sales) are of correct type and dates as datetime.

## 🧼 Example Summary of Changes

- Removed 5 duplicate rows
- Filled 12 missing 'customer_name' values with "Unknown"
- Standardized 'Gender' column to: ['Male', 'Female']
- Converted 'order_date' to datetime format
- Renamed columns: "Order Date" → "order_date", "Sales Amount" → "sales_amount"
- Casted 'quantity' and 'age' columns to integer
