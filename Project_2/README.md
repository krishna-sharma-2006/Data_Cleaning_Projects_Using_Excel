\# 📊 Data Cleaning Project using Excel



This project demonstrates the process of cleaning and preparing a raw dataset using Microsoft Excel. The goal was to transform inconsistent and unstructured data into a clean, standardized, and analysis-ready format.



\---



\## 🚀 Objective



\- Clean and standardize raw dataset  

\- Handle inconsistent values and missing data  

\- Improve data quality for analysis  



\---



\## 📂 Dataset Overview



The dataset contained multiple issues such as:

\- Inconsistent text values  

\- Missing data  

\- Mixed formatting  

\- Unstructured entries  



\---



\## 🔍 Problems Identified



\- Inconsistent entries in Gender column  

\- Missing values in Age column  

\- Irregular formatting across multiple columns  

\- Mixed values in Is\_Active column  

\- Unclean values in Hourly\_rate (USD)  

\- Misaligned rows and columns  



\---



\## 🛠 Data Cleaning Steps



\### 1. Fixed Dataset Structure

\- Corrected row and column alignment  

\- Ensured consistent table format  



\---



\### 2. Standardized Gender Column

\- Found inconsistent values such as:

&#x20; - f, female, Female, m, male, Male  

\- Standardized into:

&#x20; - Female  

&#x20; - Male  



\---



\### 3. Handled Missing Values in Age

\- Identified null values in the Age column  

\- Checked for outliers using Box Plot  

\- Since no significant outliers were found, missing values were filled using the average (mean)  



\---



\### 4. Standardized Text Formatting

* Applied formula:

```excel

=TRIM(PROPER(value))

* Ensured:

\- Removes extra spaces

\- Converts text into proper case



\### 5. Cleaned Hourly\_rate(USD)

1\. Removed unwanted symbols (like $, commas)

2\. Extracted numeric value

3\. Converted into proper currency format



\### 6. Standardized Is\_Active Column

* Original values:

&#x20;   - N, n, False, Y, Yes, True

* Converted into consistent format:

&#x20;   - Yes

&#x20;   - No



\### 🧰 Tools \& Techniques Used

* Microsoft Excel
* Functions:

&#x09;- TRIM

&#x09;- PROPER

* Data Cleaning Techniques:

&#x09;- Standardization

&#x09;- Missing value handling

&#x09;- Data formatting

* Visualization:

&#x09;- Box Plot (for outlier detection)



\### 📈 Results

* Dataset is now clean and consistent

&#x09;- Missing values handled effectively

&#x09;- Text and categorical data standardized

&#x09;- Numeric columns properly formatted

👉 The dataset is now ready for analysis.



\### 💡 Key Learnings

* Importance of data consistency
* Handling missing values using statistical methods
* Standardizing categorical data
* Practical use of Excel functions in data cleaning



⭐ Note

* This project is part of my journey in learning Data Analysis and Data Science and demonstrates practical data cleaning skills using Excel.



