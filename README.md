# ElevateLabs_Task1_DataCleaning
Data cleaning of Customer Personality Analysis dataset using Python (pandas)

# 🧠 Task 1: Data Cleaning – Customer Personality Analysis

### 📍 Internship: Elevate Labs  
**Duration:** 15-day Data Analytics Challenge  
**Task Objective:**  
Clean the dataset by handling missing values, duplicates, text inconsistencies, and outliers using Python (Pandas).

---

## 📂 Files Included
| File | Description |
|------|--------------|
| `marketing_campaign.csv` | Original dataset |
| `Elevate_Tasks.ipynb` | Python script used for data cleaning |
| `Cleaned_Customer_Personality.csv` | Final cleaned dataset |

---

## 🧹 Steps Performed
1. **Loaded Dataset** – Imported the dataset using Pandas and checked structure using `.info()` and `.describe()`.  
2. **Handled Missing Values** –  
   - Numeric columns filled with **median**.  
   - Categorical columns filled with **mode**.  
3. **Removed Duplicates** – Deleted all duplicate rows using `.drop_duplicates()`.  
4. **Cleaned Column Names** – Standardized to lowercase and replaced spaces with underscores.  
5. **Cleaned Text Data** – Trimmed whitespaces and converted text to lowercase for uniformity.  
6. **Converted Date Columns** – Transformed `Dt_Customer` into proper datetime format using `pd.to_datetime()`.  
7. **Handled Outliers** – Used **IQR (Interquartile Range)** method to cap extreme values in numeric columns.  
8. **Saved Final Dataset** – Exported cleaned data as `Cleaned_Customer_Personality.csv`.

---

## 📊 Libraries Used
- **pandas**
- **numpy**

To install the libraries:
```bash
pip install pandas numpy
```
---
*Created by Komal for the Data Analyst Internship Program.*
