# Netflix Data Cleaning Task

## Task Overview
This task involves cleaning and preprocessing the Netflix Movies and TV Shows dataset using Python and the Pandas library.

## What I Did
- Loaded the original dataset (`netflix_titles.csv`)
- Identified and handled missing values in columns like `director`, `cast`, and `country`
- Removed duplicate rows
- Standardized text formats (e.g., gender, country names if applicable)
- Converted the `date_added` column to proper datetime format using `pd.to_datetime()`
- Extracted numeric values from the `duration` column
- Renamed column headers to lowercase and replaced spaces with underscores
- Checked and fixed data types for consistency

## Files Included
- `netflix_titles.csv`: Original dataset from Kaggle
- `Task1 Data Cleaning and Preprocessing.ipynb`: Python code used for cleaning
- `netflix_cleaned.csv`: Final cleaned dataset ready for analysis
- `README.md`: This file

## Tools Used
- Python
- Pandas

