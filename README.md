# SWYNEX Data Cleaning & Preparation

## Project Overview

This project was completed as part of the SWYNEX Data Analyst Internship. The objective was to clean and prepare a public Titanic dataset for further analysis.

## Dataset

The Titanic dataset contains passenger information such as:
- Passenger ID
- Survival status
- Passenger class
- Name
- Sex
- Age
- Family information
- Ticket
- Fare
- Cabin
- Embarked port

## Data Cleaning Performed

### 1. Missing Values
- Age: 177 missing values were replaced using the median age.
- Cabin: 687 missing values were replaced with "Unknown".
- Embarked: 2 missing values were replaced using the most frequent value.

### 2. Duplicate Records
- Checked for duplicate rows.
- Found 0 duplicate records.

### 3. Data Types
- Checked the data types of all columns.
- Confirmed that the columns had appropriate data types for analysis.

### 4. Inconsistent Values
- Checked categorical values in the Sex and Embarked columns.
- No obvious inconsistent values were found.

## Tools Used

- Python
- Pandas
- Google Colab
- GitHub

## Output

The cleaned dataset is available as:

`titanic_cleaned.csv`

## Learning Outcome

Through this project, I practiced data cleaning, missing-value handling, duplicate detection, data-type validation, consistency checking, and preparing a dataset for further analysis.
