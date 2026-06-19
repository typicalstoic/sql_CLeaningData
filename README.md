# World Layoffs Data Cleaning Project

## Project Overview

This project focuses on cleaning and preparing a real-world layoffs dataset using SQL. The raw dataset contained duplicate records, inconsistent formatting, missing values, and data quality issues that could negatively affect analysis and reporting.

The objective was to transform the dataset into a clean, reliable, and analysis-ready format suitable for business intelligence, reporting, and further exploratory data analysis.

## Dataset

The dataset contains information about company layoffs worldwide, including:

- Company Name
- Location
- Industry
- Total Employees Laid Off
- Percentage Laid Off
- Date
- Company Stage
- Country
- Funds Raised

## Technologies Used

- MySQL
- SQL
- Window Functions
- Common Table Expressions (CTEs)

## Data Cleaning Steps

### 1. Data Staging

Created staging tables to preserve the original dataset and perform transformations without modifying the raw data.

### 2. Duplicate Removal

Used the `ROW_NUMBER()` window function to identify duplicate records and remove redundant entries.

### 3. Data Standardization

- Trimmed whitespace from company names
- Standardized industry values
- Cleaned country names
- Fixed inconsistent text formatting

### 4. Date Conversion

Converted date values from text format into SQL DATE format using `STR_TO_DATE()`.

### 5. Handling Missing Values

- Replaced blank values with NULL
- Filled missing industry values using matching company records
- Removed records with insufficient layoff information

### 6. Final Cleanup

Removed temporary columns used during the cleaning process and prepared the dataset for analysis.

## SQL Skills Demonstrated

- Data Cleaning
- Data Transformation
- Data Validation
- Window Functions
- CTEs
- Joins
- UPDATE Statements
- DELETE Statements
- Handling Missing Data
- Duplicate Detection

## Outcome

Successfully transformed a raw layoffs dataset into a clean and analysis-ready dataset suitable for:

- Exploratory Data Analysis (EDA)
- Business Reporting
- Dashboard Development
- Data Visualization
