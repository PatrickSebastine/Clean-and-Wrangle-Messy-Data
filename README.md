# Clean and Wrangle Messy Data  
This is a Python script to clean and wrangle a messy dataset. The dataset contains 101 rows and 12 columns with encoding and delimiter errors, missing values, inconsistent and invalid data types, duplicated rows, invalid characters, and misspelt words.

## Getting Started
1.	Make sure that Python 3 is installed.
2.	Install the necessary libraries.
3.	Load the dataset 'messy_data.csv'.
4.	Perform the cleaning and wrangling.
5.	The cleaned dataset will be saved as 'cleaned_messy_data.csv'.

## Dependencies
The script uses the following libraries:  
  •  pandas  
  •  numpy  
  •  re  
  •  warnings  

## Cleaning Process
The cleaning process includes the following steps:
1.	Load the dataset into a pandas DataFrame and correct the delimiter and encoding errors.
2.	Make all the column headers lowercase and drop the empty unnamed column.
3.	Rename some column names for easy reference.
4.	Replace "Inf" and "Nan" with NaN in the dataset.
5.	Check for rows containing null or missing values and drop them.
6.	Check for duplicated rows and drop them.
7.	Reset the row index numbers.
8.	Clean each column as follows:

## Output
The script outputs a cleaned dataset in CSV format named 'cleaned_messy_data.csv' that has 71 rows and 11 columns.

