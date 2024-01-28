# Customer Call List Data Cleaning

This Python script utilizes Pandas to clean and preprocess a customer call list stored in an Excel file ('Cleaning Data.Customer Call List.xlsx'). The cleaning operations include removing duplicates, dropping unnecessary columns, standardizing phone numbers, and handling various text manipulations.

## Features

- Loading the dataset from an Excel file.
- Removing duplicate records from the dataset.
- Dropping unnecessary columns ('Not_Useful_Column' and 'Address').
- Standardizing last names, phone numbers, and other text fields.
- Converting 'Paying Customer' and 'Do_Not_Contact' columns to binary (Y/N).
- Handling missing or null values.

## Getting Started

1. **Load Dataset:**
   - Ensure the 'Cleaning Data.Customer Call List.xlsx' file is in the specified location.

2. **Run the Script:**
   ```python
"CleaningData.CustomersList.ipynb"
