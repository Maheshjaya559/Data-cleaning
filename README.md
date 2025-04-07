# 📊 AI, ML, and Data Science Salary Analysis (2020–2025) - Data Cleaning in Excel

This project demonstrates end-to-end data cleaning and preprocessing using **Microsoft Excel**, focused on salary trends in **Artificial Intelligence (AI)**, **Machine Learning (ML)**, and **Data Science** from **2020 to 2025**.

## 📁 Repository Contents

- `Raw_Data.xlsx` – Original, uncleaned dataset
- `Cleaned_Data.xlsx` – Final cleaned dataset ready for analysis
- `Data_Cleaning_Steps.xlsx` – Step-by-step documentation of all cleaning operations within Excel
- `Interview_Questions.docx` – Common Excel-based data cleaning interview questions with answers
- `README.md` – Project overview and cleaning summary

---

## 🎯 Project Objective

To clean and prepare a raw dataset containing job and salary information from the AI/ML/Data Science domain between 2020 and 2025. The goal is to make the dataset consistent, structured, and analysis-ready using only **Excel tools and functions**.

---

## 🧹 Excel Data Cleaning Steps

All cleaning steps were performed using **Microsoft Excel** and are clearly documented in the `Data_Cleaning_Steps.xlsx` file:

### 1. **Handling Missing Values**
- Identified using `ISBLANK()`
- Filled missing values where appropriate
- Removed rows with critical missing data

### 2. **Removing Duplicates**
- Used `Remove Duplicates` to eliminate repeated rows

### 3. **Standardizing Column Headers**
- Cleaned column names for readability and consistency (e.g., "Job_Title" → "Job Title")

### 4. **Correcting Inconsistencies**
- Applied `TRIM()`, `PROPER()`, `UPPER()` to fix formatting issues
- Fixed inconsistent labels for job titles, companies, locations, and employment types

### 5. **Splitting and Combining Columns**
- Used `Text to Columns` to split combined fields (e.g., "Location")
- Merged fields where needed using `&` or `CONCATENATE()`

### 6. **Data Type Formatting**
- Converted salary values to number format
- Standardized all date formats to `YYYY-MM-DD`

### 7. **Outlier Detection (Basic)**
- Used conditional formatting to highlight unusually high or low salary values
- Manually reviewed flagged records

### 8. **Data Validation**
- Applied drop-downs for standard fields (e.g., Employment Type)
- Used `Data Validation` to restrict invalid entries

### 9. **Formulas Used**
- `IF()`, `LEN()`, `FIND()`, `TEXT()`, `SUBSTITUTE()`, `ISNUMBER()`, etc., for logic and transformation

### 10. **Documentation**
- Each step is explained in a dedicated sheet within `Data_Cleaning_Steps.xlsx` for transparency and reproducibility

---

## 📌 Tools Used

- Microsoft Excel 2016+
- Built-in Excel features: Data Validation, Text to Columns, Conditional Formatting, Filters
- Excel formulas and logic functions

---

## 📑 Key Insights (Post-Cleaning)

- Ready-to-analyze data on salary trends across roles and years
- Standardized categories and formatting ensure accuracy in future analysis or visualization

---

## 🤝 Contributing

Contributions, suggestions, or improvements are welcome. Feel free to fork the repo or submit a pull request.




