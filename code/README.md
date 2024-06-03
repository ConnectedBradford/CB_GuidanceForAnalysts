# FDM built check_rowCounts Code

The R and python scripts loops through each table in the list, and it uses the `get_row_count` function to compare the number of rows in the source and target tables. If the row counts match, the script prints a message saying so. If the row counts do not match, the script prints a message indicating that there is a discrepancy.

Similary, The Search_facility R script is designed to search a specific table in a Google BigQuery dataset for rows that contain a specified search phrase in a specified column. 
Note: If an error occurs during the execution of the function, it will be caught by the `tryCatch` block, and an error message will be printed to the console.
