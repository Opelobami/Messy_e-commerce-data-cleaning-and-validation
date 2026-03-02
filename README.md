# 🛒Messy_e-commerce-data-cleaning-and-validation
This repository documents a complete end-to-end data cleaning and validation workflow using a raw, inconsistent e-commerce dataset.

## Project Objectives
- Profile the raw dataset to identify quality issues
- Clean and standardize inconsistent fields
- Remove duplicates and correct structural errors
- Enforce data integrity rules
- Produce an analytics-ready dataset

---

# 🛠Tools & Techniques Used
- SQL for data profiling and validation queries
- Data type corrections and normalization
- Constraint checks (null, uniqueness, foreign key logic)
- Outlier detection for pricing and quantities
- Category standardization
- Date format harmonization

---

## Dataset
- 5000 rows of messy e-commerce data
- Contains data quality issues:
  - Missing values
  - inconsistent date format
  - Pricing and quanity errors
  - Inconsistent customer names, product, shipping address and payment status

  ---

  ## Data cleaning steps
1. Load the data into a new Excel sheet and convert into table.
2. Using the filter button, I standardized inconsistent categorical fields (customer_name, product, shipping address and payment status) one after the other.
3. Converted the categorical value in Quantity to numerical value and replaced missing values with NULL because zero is an actual number and mean or median does not depict the actual value. Null means we do not know the value.
4. Replaced missing and error values in price with NULL since we are not privy to the actual value. NULL indicates that we do not know which is preferable to replacing with 0 or mean or median. 
5. Used custom column in power query to standardize date.

---

## Why This Project Matters
Accurate, clean data is the foundation of reliable business insights. This project highlights the importance of:
- Preventing incorrect analysis and reporting
- Improving decision-making based on trustworthy data
- Ensuring consistency across e-commerce data table
- Building repeatable data quality and validation processes

---

## Key Learnings
- How to systematically identify and resolve missing, duplicate, and inconsistent data
- Best practices for handling missing values (using NULL vs 0 or averages)
- Techniques for standardizing categorical fields and date formats
- Importance of documenting every cleaning and validation step for transparency

🔗 **[View messy and clean dataset here--->](https://drive.google.com/drive/folders/1jsdaMhQEuwKJcn-bqkS7Flg-sKx7oyj7?usp=drive_link)**

---

## Contact  

Let’s connect or collaborate on **Business Intelligence, Data Analytics, or SQL projects** 👇  

**👤 Name:** Opeyemi Ayodeji  
**🔗 LinkedIn:** [Opeyemi Ayodeji](https://www.linkedin.com/in/opeyemi-ayodeji-86a696b0/)  
**📧 Email:** sopeyemi65@gmail.com  
