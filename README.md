# Data Analyst Internship - Task 1
## Dataset: Mall Customers

### Objective:
Clean and preprocess the raw dataset (Mall_Customers.csv) by handling missing values, duplicates, inconsistent formats, and preparing it for analysis.

### Changes Made:
- Removed duplicate rows
- Handled missing values (forward fill method used)
- Standardized gender values (`male`, `female`)
- Cleaned column headers (lowercase, underscores instead of spaces)
- Ensured correct data types (e.g., Age as integer)
- Final dataset ready for analysis (200 rows × 5 columns)

### Files in Repository:
- **Mall_Customers.csv** → Raw dataset
- **Mall_Customers_Cleaned.csv** → Cleaned dataset
- **data_cleaning_mall_customers.ipynb** → Jupyter/Colab notebook with code
- **README.md** → Summary of cleaning process

### Tools Used:
- Python (Pandas)
- Google Colab

### How to Run:
1. Open `data_cleaning_mall_customers.ipynb` in Google Colab.
2. Upload `Mall_Customers.csv` when prompted.
3. Run all cells to clean the dataset.
4. The cleaned dataset will be saved as `Mall_Customers_Cleaned.csv`.
