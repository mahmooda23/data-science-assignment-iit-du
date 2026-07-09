# Data Science Assignment | Salary Data Analysis
**An academic project under the Institute of Information Technology, University of Dhaka**

## Problem Statement
The objective of this project is to clean, preprocess, and analyze a global salary survey dataset. The goal is to evaluate compensation trends across different demographic groups by standardizing various currencies to a single metric (Bangladeshi Taka - BDT) and analyzing the average total compensation across structured age categories.

## Key Tasks & Objectives
1. **Data Ingestion:** Load the raw survey dataset (`salary.csv`).
2. **Column Renaming:** Standardize verbose and descriptive survey questions into concise, workable column names (e.g., `Annual_salary`, `Additional_salary`, `Currency`, `Age`).
3. **Data Deduplication:** Identify and remove duplicate entries based on annual and additional salary combinations.
4. **Handling Missing Values:**
   - Fill null values in additional compensation with `0`.
   - Drop records that are missing the primary annual salary.
5. **Data Type Casting & String Manipulation:** Clean formatting issues (such as commas in salary text) and convert salary features to numerical data types.
6. **Feature Engineering:** Compute `Total_Salary` by combining annual and additional monetary compensation.
7. **Currency Standardization:** 
   - Filter the dataset to isolate target currencies (USD, CAD, EUR).
   - Convert these local currencies into Equivalent BDT using standard exchange rates.
8. **Data Discretization (Binning):** Clean the `Age` column to handle edge cases ('under 18', '65 or over') and bin the continuous numerical ages into structured demographic categories.
9. **Aggregation & Analysis:** Group the transformed data by age category to calculate and determine which age demographic receives the highest average equivalent compensation in BDT.

## Repository Contents
* `Salary_Data_Analysis.ipynb`: The main Jupyter Notebook containing the Python codebase for data preprocessing and analysis.
* `salary.csv`: The raw dataset used for the assignment.

## Author
**Mahmuda Khatun**  
*PGD in Information Technology*  
*Institute of Information Technology, University of Dhaka*
