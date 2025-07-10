# Data-Cleaning-and-Preprocessing
Task 1:Data Cleaning and Preprocessing

*NAME*: KAVANASHREE

*COMPANY*: SaiKet SYSTEMS

*INTERN ID*: SKS/A2/C24561

*PROJECT DETAILS*:

This project involved five steps, all of which aimed at data cleaning and pre-processing. The steps I followed are:

1) Loading the data: First, I loaded the dataset and examined its structure.

2) Handling missing values: From initial inspection, the main column with missing values appears to be TotalCharges (with some empty strings). I'll handle this by:

Converting empty strings to NaN

Filling missing values with appropriate substitutes (0 for new customers, median for others)

3) Converting categorical variables: The dataset contains several categorical variables that need encoding:

Binary categorical variables (Yes/No) - convert to 1/0

Multi-category variables - use one-hot encoding

Ordinal variables (like Contract) could use ordinal encoding or one-hot encoding

4) Final data checking: Checking if the initial steps worked or do they need any other changes done

5) Saving the cleaned data
