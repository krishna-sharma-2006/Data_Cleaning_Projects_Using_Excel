# 📊 Data Cleaning Report: FIFA 21 Dataset (Excel)

This project presents a complete data cleaning process performed on the FIFA 21 dataset using Microsoft Excel. The objective was to transform raw and inconsistent data into a structured and analysis-ready format.

---

## 🚀 Objective

- Clean messy real-world dataset
- Handle inconsistencies and missing values
- Standardize formats for analysis
- Improve overall data quality

---

## 📂 Dataset Overview

The dataset contains player-related information such as:
- Club details  
- Dates  
- Performance metrics (e.g., Hits)  

Initially, the dataset contained multiple issues including formatting inconsistencies, missing values, and irregular data entries.

---

## 🔍 Problems Identified

- Inconsistent row and column structure  
- Line breaks within cells (especially in Club column)  
- Missing values  
- Mixed date formats  
- Non-standard numeric values (e.g., `1.6K`, `2.3K`)  
- Duplicate records  

---

## 🛠 Data Cleaning Steps

### 1. Fixed Dataset Structure
- Corrected row and column alignment
- Ensured consistent table format

---

### 2. Cleaned Club Column
- Removed unnecessary line breaks inside cells
- Standardized text formatting

---

### 3. Handled Missing Values
- Replaced blank cells with 'NA'
- Maintained consistency across dataset

---

### 4. Standardized Date Formats
- Converted all date columns into a uniform format
- Ensured compatibility for analysis

---

### 5. Converted Hits Column (Important Step 🔥)

Some values were stored like:
1.6K, 2.3K

These were converted into numeric format using:

=IF(RIGHT(cell,1)="K", VALUE(LEFT(cell,LEN(cell)-1))*1000, cell)

✔ Example:
- 1.6K → 1600
- 2.3K → 2300

---

### 6. Removed Duplicates
- Identified and removed duplicate rows
- Ensured data integrity

---

## 🧰 Tools & Functions Used

- Microsoft Excel  
- Functions:
  - IF
  - VALUE
  - LEFT
  - RIGHT
  - LEN
  - TRIM
  - PROPER
- Features:
  - Remove Duplicates  
  - Find & Replace  
  - Formatting tools  

---

## 📈 Results

After cleaning:
- Dataset became consistent and structured  
- Numeric values were properly formatted  
- Dates were standardized  
- Duplicate entries were removed  

👉 The dataset is now ready for analysis and visualization.

---

## 💡 Key Learnings

- Handling messy real-world data  
- Data preprocessing using Excel  
- Importance of data consistency  
- Practical use of Excel formulas  

---

## 🚀 Future Improvements

- Add data visualization (charts/dashboard)  
- Use Power Query for advanced cleaning  
- Automate cleaning process  
- Expand dataset for deeper analysis  

---

## 📖 Author

- Krishna Sharma  

---

## ⭐ Note

This project is part of my journey in learning Data Analysis and Data Science and demonstrates practical data cleaning skills using Excel.
