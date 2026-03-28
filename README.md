# Crowdfunding ETL Project

# Overview
This project demonstrates a complete ETL pipleline using Python, Pandas, and PostgreSQL. The goal is to process raw crowdfunding data, transform it into structure formats, and load it into a relational database for analysis.

**Objectives**: 
* Extract raw data from Excel files
* Transform and normalize datasets using Python and Pandas
* Generate clean, analysis-ready CSV files
* Design a relational database schema (ERD)
* Load data into a PostgreSQL database with enforced relationships

## ETL Workflow

**Extract:** Load data from Excel files ( [crowdfunding.xlsx](https://github.com/TMJ30/Crowdfunding_ETL/blob/main/Resources/crowdfunding.xlsx), [contacts.xlsx](https://github.com/TMJ30/Crowdfunding_ETL/blob/main/Resources/contacts.xlsx) )
     
**Transform**
* Cleaned and standardized columns
* Split category and subcategory data
* Created unique IDs from relational mapping
* Converted data types (floats, timestamps)
* Parsed contact names into first/last

**Load**
* Exported cleaned data to CSV files
* Created relational schema in PostgreSQL
* Imported data into tables with foreign key relationships



2. **Campaign Data**
 * Split combined fields into normalized columns
 * Generated keys:
   * `category_id`
   * `subcategory`
