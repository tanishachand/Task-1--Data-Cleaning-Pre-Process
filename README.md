# Task-1-Data-Cleaning-Pre-Process
Summary of Preprocessing Actions
Data preprocessing for the Kaggle Netflix dataset was executed in Excel and involved several key cleaning actions:
Header Standardization: Column names were consistently formatted (e.g., to lowercase or uppercase, with underscores eliminated) for uniformity.
Missing Data Imputation: A filter was applied to identify blank entries. For fields like Director, cast, and country, all missing values were explicitly replaced with the placeholder UNKNOWN.
Deduplication: The entire dataset was checked for and had duplicate rows removed using the REMOVE DUPLICATES feature.
Date Formatting: The date column was restructured to the DD-MM-YYYY standard.
Text Unification: Country names were standardized, such as changing all instances of "United States" to USA and "United Kingdom" to UK , Listed_in was converted to Listed_Type
