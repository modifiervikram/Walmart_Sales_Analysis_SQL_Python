

# Walmart Sales Data Analysis (SQL_Python)

##  Project Overview
End-to-end analysis of Walmart sales data using Python and SQL. Performed data cleaning, feature engineering, and loaded data into MySQL &amp; PostgreSQL. Executed SQL queries to analyze revenue, sales trends, and branch performance, with documentation in Jupyter Notebooks.

## Tech Stack
- **Languages/Tools:** Python (pandas, numpy), SQLAlchemy, MySQL, PostgreSQL
- **Documentation:** Jupyter Notebooks, PDF (Business Problems)

##  Project Workflow
1. **Data Preparation**
   - Collected Walmart dataset (Kaggle)
   - Cleaned missing values, duplicates, and type inconsistencies
   - Engineered new features (e.g., *Total Amount = Unit Price × Quantity*)

2. **Database Integration**
   - Loaded cleaned data into MySQL & PostgreSQL via SQLAlchemy
   - Verified with initial queries and schema validation

3. **Business Problem Solving**
   - Solved multiple business questions (documented in PDF):
     - Revenue trends by branch and product category
     - Best-selling products
     - Customer purchase behavior (time, city, payment methods)
     - Profit margin analysis
   - Each solution written as SQL query and tested in databases

4. **Documentation**
   - Jupyter Notebooks for Python workflow
   - SQL scripts for queries
   - Business Problems PDF included under `/docs`

## 📊 Key Insights
- Identified high-performing branches and categories
- Detected sales trends across weekdays and peak hours
- Analyzed customer payment preferences
- Suggested profitability improvement strategies

##  Repository Structure
```plaintext
data/                # Dataset files  
sql_queries/         # SQL scripts for analysis  
notebooks/           # Python notebooks for cleaning & feature engineering  
docs/                # Business Problems PDF & additional docs  
README.md            # Project documentation  
requirements.txt     # Python dependencies  
main.py              # Script for ETL workflow  
