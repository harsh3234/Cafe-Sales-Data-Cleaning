# ☕ Cafe Sales Data Cleaning & Preparation Pipeline

## 📌 Project Summary

This project demonstrates a complete **data cleaning and preprocessing workflow** applied to a real-world, messy cafe sales dataset. The objective was to transform unreliable raw data into a **high-quality, analysis-ready dataset**, suitable for business intelligence, analytics, and machine learning tasks.

By implementing systematic data validation, correction, and standardization techniques, this project showcases practical data engineering and analytics skills using Python.

---

## 🎯 Key Objectives

* Identify and diagnose data quality issues
* Design a reproducible data cleaning pipeline
* Improve dataset accuracy, consistency, and usability
* Deliver a clean dataset ready for downstream analysis

---

## 🛠️ Technology Stack

* **Programming Language:** Python
* **Libraries:** Pandas, NumPy
* **Tools:** Jupyter Notebook

---

## 🧹 Data Quality Issues Resolved

The raw dataset (`dirty_cafe_sales.csv`) contained multiple real-world data problems:

### 1️⃣ Computational Errors

* Corrected `"ERROR"` values in the `total_spent` column
* Recalculated using the formula:

  ```
  total_spent = price_per_unit × quantity
  ```

### 2️⃣ Missing & Invalid Values

* Handled `"UNKNOWN"` and null values in critical columns:

  * `item`
  * `payment_method`
  * `location`
* Applied logical imputation strategies to preserve data integrity

### 3️⃣ Data Consistency & Standardization

* Standardized date formats in `transaction_date`
* Cleaned and formatted numerical fields
* Improved categorical consistency
* Enhanced readability with uniform formatting

---

## 📊 Outcome & Impact

* ✅ Increased dataset reliability and accuracy
* ✅ Reduced missing and inconsistent values
* ✅ Created a structured dataset ready for analytics
* ✅ Built a reusable data cleaning workflow

This project reflects real-world data cleaning challenges commonly faced in analytics and data science roles.

---

## 🚀 How to Run the Project

1. Clone the repository
2. Install dependencies:

   ```
   pip install pandas numpy
   ```
3. Open the Jupyter Notebook in the `notebooks/` folder to explore the full cleaning pipeline.

---

## 💡 Key Learnings

* Practical handling of messy real-world datasets
* Data validation and transformation techniques
* Importance of reproducible data pipelines
* Improved proficiency in Pandas and NumPy

I can also write a **GitHub description**, **LinkedIn project explanation**, and **resume-ready version** for this project.
