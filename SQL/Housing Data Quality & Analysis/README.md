# Housing Data Quality & Analysis (SQL)

## Project Overview
This project focuses on cleaning and transforming a housing dataset using SQL to improve data consistency and prepare it for analysis and reporting.

The dataset contains approximately 56,000 housing records from Nashville and was used to practice common data cleaning and transformation techniques.

---

## Objective
- Clean and standardize housing data using SQL  
- Handle missing and inconsistent values  
- Prepare a structured dataset suitable for analysis and reporting  

---

## Tools & Technologies
- SQL  
- Microsoft SQL Server (SSMS)  

---

## Data Source
Sample Nashville housing dataset used for SQL data cleaning and transformation practice.

---

## Data Cleaning & Transformation
The following data preparation steps were performed using SQL:

- Standardized date formats using `CONVERT`  
- Populated missing property address values using `SUBSTRING`, `CHARINDEX`, and `ISNULL`  
- Split address fields into individual columns (Address, City, State) using `PARSENAME` and `REPLACE`  
- Converted `"Y"` and `"N"` values to `"Yes"` and `"No"` in the *Sold as Vacant* field using `CASE` statements  
- Removed duplicate records using `ROW_NUMBER()` with `PARTITION BY`  
- Dropped unused and irrelevant columns to simplify the dataset  

---

## Outcome
The final output is a clean, structured housing dataset suitable for downstream analysis, reporting, or visualization tasks.
