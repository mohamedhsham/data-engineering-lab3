# Data Engineering - Lab 3 Assignment

# Project Overview
This project profiles and cleans the January 2021 NYC Yellow Taxi dataset using Python and Pandas.

# Dataset used
January 2021 NYC Yellow Taxi Trip Records.

# Tools or Apps used
- Python
- Pandas
- Jupyter Notebook
- uv

# Data Processing
The dataset is processed in chunks of 100,000 rows to avoid loading the entire file into memory.

# Data Quality Checks
- Invalid pickup and drop-off dates
- Negative or zero fares
- Negative or zero trip distances
- Zero passenger counts
- Duplicate records

# Cleaning Rules
- Remove records with invalid pickup dates.
- Remove records with missing passenger counts.
- Remove records with negative or zero fares.
- Remove duplicate records.
- Flag suspicious drop-off dates, trip distances, and zero passenger counts.

# Results
- Original records: 1,369,765
- Cleaned records: 1,264,125
- Removed records: 105,640
