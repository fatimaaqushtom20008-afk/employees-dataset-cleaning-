# Employees Dataset Cleaning Report

## Overview
The Employees dataset was cleaned and formatted to improve data quality, consistency, and readability.

## Cleaning Steps

### 1. Removed Duplicates
All employee records were checked for repeated rows. Duplicate rows were removed so that each record appears only once.

### 2. Fixed Missing Data
Blank cells in the **First Name** and **Team** columns were identified and replaced with **Unknown** instead of leaving them empty.

### 3. Fixed Formatting Errors
Column widths were adjusted so headers and values are fully visible. Date columns were also formatted so values display correctly instead of appearing as `###`.

### 4. Checked Data Types
The **Salary** column was formatted as currency, while **Bonus %** was formatted as a percentage to ensure the values are displayed and interpreted consistently.

## Result
The cleaned workbook is saved as `employees_cleaned.xlsx`.

The cleaning process improves readability and consistency while preserving the original employee information.
