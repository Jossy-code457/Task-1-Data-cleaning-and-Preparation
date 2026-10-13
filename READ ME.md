### **Air Quality Dataset Cleaning**

##### **1. Project Overview**

This project involves cleaning an air quality dataset using Microsoft Excel. The aim was to identify missing values, check for duplicate records, examine data types, and investigate inconsistent values.



##### **2. Dataset Information**

* Tool used: Microsoft Excel
* Number of records: 9,357
* Number of columns: 15



##### **3. Data Cleaning Steps**

* **Missing Values**

The value -200' was used to represent missing or unavailable measurements. I replaced these values with blank cells. Excel reported 16,701 replacements.

The blank cells were retained to indicate missing measurements rather than inserting estimated values.



* **Duplicate Records**

I used Excel's Remove Duplicates feature to check for duplicate records. Excel reported that no duplicate values were found.



* **Data Types**

I checked the measurement columns for non-numeric entries using Excel formulas. All checks returned zero non-numeric, non-blank entries.

I also checked the date entries and standardized the display formats of the Date and Time columns.



* **Inconsistent Values**

I checked selected measurements for potentially invalid values:

* CO(GT): No negative values were found.
* RH: No values below 0 or above 100 were found.
* AH: No negative values were found.
* T: Minimum value of -1.9 and maximum value of 44.6.
* C6H6(GT): Minimum value of 0.1 and maximum value of 63.7.

The observed minimum and maximum values were recorded for review and were not changed solely because of their magnitude.



##### **4. Output**

The cleaned dataset is saved as `Air\_Quality\_Cleaned.xlsx`.



##### **5. Limitations**

Missing measurements remain blank. No estimated values were inserted to replace them.



