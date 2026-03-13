# Nashville Housing Data Cleaning Project (SQL)

Project Overview


This project focuses on cleaning and preparing the Nashville Housing dataset using Microsoft SQL Server through Microsoft SQL Server Management Studio, with additional data handling performed in Microsoft Excel.
In real-world data analysis, datasets often contain missing values, inconsistent formats, and duplicate records. The goal of this project was to clean and transform the dataset so it becomes structured, accurate, and ready for further analysis or visualization.
This project demonstrates common data preparation techniques used by analysts before building reports or dashboards.

# Tools Used

Microsoft SQL Server

Microsoft SQL Server Management Studio

Microsoft Excel

# Dataset

The project uses the Nashville Housing dataset, which includes information about property sales such as:

Property address
Owner details
Sale price
Sale date

# Location information

The dataset required several cleaning steps to improve data quality and structure.
Data Cleaning Process

1. Data Import
The dataset was imported and reviewed to identify inconsistencies and data quality issues.
2. Standardizing Date Formats
Sale date fields were converted into a consistent date format for easier analysis.
3. Handling Missing Values
Missing property addresses were identified and populated using related records with matching parcel IDs.
4. Splitting Address Fields
Combined address columns were split into separate columns such as street address, city, and state.
5. Data Standardization
Certain categorical values were standardized for clarity and consistency.

# Example:

Y → Yes
N → No

7. Removing Duplicate Records
Duplicate entries were identified using SQL window functions and removed to maintain data accuracy.
8. Final Data Preparation
The cleaned dataset was exported for further analysis and potential visualization.

# Skills Demonstrated

SQL Data Cleaning
Data Transformation
Handling Null Values
Data Standardization
Data Preparation for Analysis
