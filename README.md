# Data Cleaning with SQL
This repository contains SQL code to clean and standardize a dataset of property sales data. The code includes steps to standardize the SaleDate, populate missing property address data, break out the address into individual columns, change 'Y' and 'N' values in the 'SoldAsVacant' column to 'Yes' and 'No' using a CASE statement, remove duplicates, and delete unused columns.<br>
Query: [Here](https://github.com/SumitxThokar/Data-Cleaning-with-SQL/blob/main/Queries/part2-Data_Cleaning.sql)

## Data Source
The original dataset is a CSV file of property sales data. <br>
File: [Here](https://github.com/SumitxThokar/Data-Cleaning-with-SQL/tree/main/Data)

## Steps for Data Cleaning
1. Standardize the SaleDate
2. Populating missing property address data
3. Break out Address into Individual column
4. Changing Y, N in 'SoldAsVacant' column into Yes, No using CASE statement
5. Removing Duplicates
6. Deleting Unused column

## Conclusion
While SQL can be a powerful tool for cleaning and transforming data, it is not always the best choice for every data cleaning task. Other tools such as Python, R, or specialized data cleaning software may be better suited for certain types of data or more complex data cleaning tasks.
