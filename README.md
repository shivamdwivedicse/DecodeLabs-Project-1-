# DecodeLabs Internship – Task 1: Data Cleaning & Preparation

## 📌 Overview
Completed **Task 1** of the DecodeLabs Data Analytics Internship.

The goal of this task was to clean and prepare a raw dataset by handling missing values, checking duplicates, correcting data formats, and preparing a clean dataset for further analysis.

---

## 🎯 Task Objectives:-
- Identify and handle missing/null values.
- Check and remove duplicates.
- Correct data formats (dates, text, numeric).
- Validate data consistency.
- Prepare a clean and analysis-ready dataset.

---

## 🛠️ Tools & Libraries Used:-
- Python.
- Pandas.
- Jupyter Notebook.

---

## 📂 Dataset Cleaning Steps Performed:-

### 1. Missing Value Handling
- Identified missing values using `.isnull().sum()`
- Filled missing values in **CouponCode** column with `No_Coupon`

### 2. Duplicate Check
- Checked dataset for duplicate rows
- Verified dataset uniqueness

### 3. Data Type Correction
- Converted **Date** column to proper `datetime` format
- Verified numeric and categorical data types

### 4. Data Validation
- Validated `TotalPrice = Quantity × UnitPrice`
- Handled floating-point precision check using rounding

### 5. Dataset Preparation
- Removed unnecessary columns:
  - `OrderID`
  - `TrackingNumber`
  - `ShippingAddress`
- Prepared final cleaned dataset

---

## 📊 Final Dataset Information:-
- **Rows:** 1200
- **Columns:** 11
- **Missing Values:** 0
- **Duplicates:** 0

Final Columns:
- Date
- CustomerID
- Product
- Quantity
- UnitPrice
- PaymentMethod
- OrderStatus
- ItemsInCart
- CouponCode
- ReferralSource
- TotalPrice

---

## 📚 Key Learnings:-
Through this task, I improved my understanding of:
- Data Cleaning.
- Data Preparation.
- Missing Value Handling.
- Data Type Conversion.
- Dataset Validation using Python & Pandas.

---

### Acknowledgement
Thanks to **DecodeLabs** for this learning opportunity.

**Dataset provided by DecodeLabs.**
