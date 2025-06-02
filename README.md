
# Data Cleaning and Preprocessing – Internship Task 1

## 📄 Dataset Used
Name: Netflix Movies and TV Shows  
Source: https://www.kaggle.com/datasets/shivamb/netflix-shows
---

## 🛠️ Tools Used
- Excel

---

## 🧹 Cleaning Steps Performed

1. **Checked for Missing Values**
   - Used `isnull()` and handled them using `fillna()` / `dropna()`
   - [Example: Filled missing 'Age' with the mean]

2. **Removed Duplicate Records**
   - Used `drop_duplicates()` function to remove duplicate rows

3. **Standardized Text Columns**
   - Made text columns lowercase using `.str.lower()`
   - Removed unwanted spaces using `.str.strip()`

4. **Formatted Dates**
   - Converted date columns to proper datetime format using `pd.to_datetime()`

5. **Renamed Columns**
   - Renamed all columns to lowercase with underscores (e.g., `CustomerID` → `customer_id`)

6. **Fixed Data Types**
   - Converted columns to appropriate types (e.g., `age` to int, `date` to datetime)

---

## ✅ Output
- Cleaned dataset: `cleaned_data.csv`
- All columns are standardized and cleaned
- Data is ready for analysis or modeling

---

## 📂 Files in This Repo
- `cleaned_data.csv`: Final cleaned dataset
- `README.md`: This file

---

## 🙋‍♂️ Done by
- Shantanu Bhadage
- 02/06/2025
