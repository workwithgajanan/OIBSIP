# Task 3: Data Cleaning & Transformation

## Overview
This project demonstrates professional-level data cleaning and preprocessing skills. The objective was to take a deliberately messy dataset (`Messy_Employee_dataset.csv`) containing missing values, formatting anomalies, and structural issues, and systematically transform it into a pristine, analysis-ready format.

---

## Tech Stack
* **Language:** Python
* **Libraries:** `pandas`, `numpy`
* **Environment:** Jupyter Notebook / Python Script

---

## Step-by-Step Data Cleaning Workflow

1. **Data Quality Audit:**
   * Inspected initial shape, column types, and duplicate counts.
   * Identified 211 missing values in `Age`, 24 missing values in `Salary`, and anomalous negative integer values in the `Phone` column.

2. **Missing Data Handling:**
   * **`Age` & `Salary`:** Imputed missing values using the **median** rather than the mean to safeguard against skewed distributions and extreme outliers.

3. **Duplicate Check:**
   * Scanned for exact row duplicates (0 duplicates found).

4. **Standardization:**
   * Converted raw `Join_Date` strings into standard `datetime` objects.
   * Corrected phone numbers by extracting absolute values (`.abs()`) and applying 10-digit zero-padding (`.str.zfill(10)`).
   * Stripped trailing or leading whitespaces across all categorical text columns.

5. **Outlier Treatment:**
   * Applied the **Interquartile Range (IQR) capping method** on numeric features (`Age` and `Salary`) to neutralize extreme anomalies while retaining total data volume.

6. **Data Type Correction:**
   * Enforced strict type mapping: IDs and phone numbers as strings, dates as `datetime`, numeric salaries as floats, and status/performance metrics as categories.

---

## "Before vs. After" Summary Table

| Metric | Before Cleaning | After Cleaning |
| :--- | :--- | :--- |
| **Total Rows** | 1,020 | 1,020 |
| **Total Null Count** | 235 | 0 |
| **Duplicate Rows** | 0 | 0 |
| **Data Type Accuracy** | Inconsistent (Strings, Negative Ints) | 100% Valid Types |

---

## Files Included in Repository
* `cleaned_employee_dataset.csv` — The finalized, cleaned dataset ready for analysis.
* `data_cleaning_script.py` (or notebook) — The source code implementing the end-to-end cleaning pipeline.
* `README.md` — Project documentation.
