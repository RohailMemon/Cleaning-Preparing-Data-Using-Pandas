Modern Arts Data Cleaning with Pandas

This project focuses on cleaning and preprocessing a modern arts dataset using Pandas in Python.
The dataset contained inconsistent formatting, missing values, and unnecessary symbols, which were cleaned to prepare it for further analysis.

📌 Key Cleaning Steps:
✔ Cleaned Gender Column – Standardized values, removed special characters, and replaced missing values with "Gender Unknown".
✔ Standardized Nationality Column – Removed extra symbols and replaced missing values with "Nationality Unknown".
✔ Formatted Date Columns (BeginDate & EndDate) – Extracted only numeric values, removed unwanted characters like (, c, C, ., s, ' ).
✔ Handled Missing Values – Used Boolean indexing to replace empty fields with appropriate labels.
✔ Converted BeginDate & EndDate to Float – Ensured date fields were numerical for further analysis.

🛠️ Technologies Used
Python 🐍
Pandas for data cleaning
Jupyter Notebook for documentation
