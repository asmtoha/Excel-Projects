# US Presidents Data Cleaning Project

This project demonstrates various data cleaning techniques using historical data of US Presidents.

## Project Overview

The project focuses on cleaning and standardizing US Presidents' historical data, showcasing essential data cleaning operations in Excel.

## File Structure

- `US_Presidents_Data_Cleaning_Tutorial.xlsx`: Main workbook containing:
  - Raw data sheet ("need to clean")
  - Cleaned data sheet ("us Preident cleaned")

## Data Fields

The dataset includes the following information about US Presidents:
- President names
- Prior experience before presidency
- Political party affiliation
- Vice presidents
- Salary information
- Date information (created and updated)

## Data Cleaning Operations

### 1. Party Name Standardization
- Standardized various party name formats:
  - "Democratic-  Republican" → "Democratic"
  - "Whig   April 4, 1841  â€"  September 13, 1841" → "Whig"
  - "Demorcatic" → "Democratic"

### 2. Date Formatting
- Standardized date formats
- Ensured consistent date representation
- Separated date fields for better analysis

### 3. Data Type Conversions
- Converted text to appropriate data types
- Standardized numeric fields
- Properly formatted date fields

### 4. Missing Value Handling
- Identified and documented missing values
- Implemented appropriate handling strategies
- Maintained data integrity

### 5. Duplicate Detection
- Identified and removed duplicate entries
- Ensured data uniqueness
- Maintained historical accuracy

## How to Use

1. Open `US_Presidents_Data_Cleaning_Tutorial.xlsx`
2. Review the "need to clean" sheet to see raw data
3. Examine the "us Preident cleaned" sheet to see cleaned data
4. Study the formulas and transformations used

## Analysis Tools

The project can be analyzed using the provided Python script:
```bash
python analyze_data_cleaning.py
```

## Best Practices Demonstrated

1. Data Standardization
2. Consistent Formatting
3. Error Handling
4. Data Validation
5. Documentation of Changes

## Notes

- All cleaning operations are documented within the Excel workbook
- Formulas used for cleaning are preserved for reference
- The cleaned dataset maintains historical accuracy while improving data quality 