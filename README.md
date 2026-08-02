# Sales Data Cleaning Using Pandas

##  Project Overview

This project focuses on cleaning a messy e-commerce sales dataset using Python and Pandas. My objective was to identify and resolve common data issues to prepare the dataset for Exploratory Data Analysis (EDA).

---

## 🛠 Dataset Issues Identified

- Missing values
- Incorrect data types
- Duplicate values
- Invalid negative values
- Inconsistent date formats
- Data validation issues

---

## 🔧 Data Cleaning Steps

### 1. Missing Value Handling
- Filled missing values in numeric columns using median values.
- Filled missing categorical values appropriately.
- Removed rows with missing order dates.

### 2. Data Type Conversion
- Converted `Order Date` to datetime format.
- Converted `Quantity` to numeric datatype.
- Converted `Price` to numeric datatype.

### 3. Duplicate Removal
- Identified and removed duplicate values.

### 4. Invalid Data Handling
- Detected negative values in `Quantity` and `Price`.
- Removed records containing invalid negative values.

### 5. Data Validation
- Verified data consistency.
- Checked null values using `isnull().sum()`.
- Examined dataset structure using `info()`.
- Generated summary statistics using `describe()`.

---

## 🧰 Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook
- VS Code

---

## 📊 Results

After cleaning:

- ✅ No missing values
- ✅ Correct data types
- ✅ Duplicate rows removed
- ✅ Invalid negative values handled
- ✅ Dataset ready for Exploratory Data Analysis (EDA)

---

## 🚀 Skills Demonstrated

- Data Cleaning
- Data Validation
- Data Type Conversion
- Missing Value Treatment
- Duplicate Detection
- Pandas Data Manipulation
- Data Quality Assessment

---

## 📁 Project Structure

```text
Sales-Data-Cleaning/
│
├── data/
│   └── ecommerce_sales_data.csv
│
├── notebook/
│   └── sales_data_cleaning.ipynb
│
├── README.md
│
└── requirements.txt
```

---

## 👨‍💻 Author

**Aman**

<img width="626" height="453" alt="{685B6349-0CB6-49BD-B1D1-8099FAB499BB}" src="https://github.com/user-attachments/assets/154b06e3-07fe-4427-be15-8b2a0553455d" />

<img width="694" height="344" alt="{4410C360-D111-443A-B94A-FD95BE5B2F52}" src="https://github.com/user-attachments/assets/4e1c849c-8e96-4e69-8d51-ad512f00d723" />

Aspiring Data Scientist | Python | Pandas | NumPy
