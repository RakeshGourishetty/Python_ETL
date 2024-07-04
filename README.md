**Crowdfunding ETL Project**
**Introduction**
ETL (Extract, Transform & Load) is crucial for managing diverse and messy data sources effectively. This project aims to extract data from contacts.xlsx and crowdfunding.xlsx, transform it using Python and pandas, and load it into a PostgreSQL database via pgAdmin. The goal is to derive clean, structured datasets for analysis and insights into crowdfunding trends.

**Sources of Data**
Data resides in the contacts.xlsx and crowdfunding.xlsx files within the Resources folder of this repository.

**Database Setup**
Database Type: Relational (SQL)
Tools Used: Jupyter Notebook for data processing with pandas, numpy, and datetime packages.
Data Loading: pgAdmin for PostgreSQL database management.

**Findings**
Identified successful categories like "theater", "film & video", and "music".
Highlighted top subcategories and countries contributing to crowdfunding success.
Detailed analysis available in the project documentation.


**Project Outline**

**Instructions**

**Category and Subcategory DataFrames:**

Extract and transform data from crowdfunding.xlsx to create category.csv and subcategory.csv.

**Campaign DataFrame:**

Extract and transform data from crowdfunding.xlsx to create campaign.csv.

**Contacts DataFrame:**

Extract contact_id, name, and email using Python dictionary methods or regular expressions from contacts.xlsx to create contacts.csv.
Crowdfunding Database:

Design and implement database schema (crowdfunding_db_schema.sql).
Create crowdfunding_db in PostgreSQL and populate tables using data from CSV files.

**Output verification**
Verify data integrity through SELECT queries.
