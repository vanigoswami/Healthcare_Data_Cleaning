# 🏥 Healthcare Data Cleaning

A concise Python pipeline to clean and prepare a patient dataset for analysis.

### 🛠️ Key Steps

* **Data Audit:** Used `df.info()` and `isnull()` to identify 25% missing data.
* **Type Casting:** Converted `age` and `weight` to numeric; `insurance` to category.
* **Imputation:** Filled numeric gaps with **Median** and categorical gaps with **Mode**.
* **Deduplication:** Dropped repeated `patient_id` records to ensure 1:1 data integrity.

### 📊 Results

* **Rows:** 20 → 17 (Unique Patients)
* **Missing Values:** 0% remaining
* **Data Types:** Optimized for analysis (Numeric/Category)
