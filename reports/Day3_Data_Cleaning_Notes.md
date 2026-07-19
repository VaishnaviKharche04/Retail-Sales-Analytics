# Day 3 : Data Cleaning Notes

## Dataset quality check

### Missing Values
- I checked missing values using `isnull().sum()`.
- The columns with missing values were 0.

### Duplicate Rows
- I checked duplicate rows or records using `duplicated().sum()`.
- Number of duplicate rows found : 17.

### Data Types
- I have checked data types using `dtypes`.
- Here there is no date column get exists.
- so, there is no need to convert it into proper date format.

### What I Learned
1. Data cleaning is important because raw data may contain missing values, duplicates, incorrect data types, and inconsistent values. Cleaning the data improves the quanlity and help us to take the better decision based on accurate information.
2. Missing values means empty or unavailable data in dataset.
3. Duplicate records can affect analysis because they can count the same transaction more than once, which can make totals, averages, counts, and other results inaccurate.
4. Dates are important for sales analysis because they help us understand sales trends over time, such as daily, monthly, and yearly performance.