# Task_1
# Data Cleaning Summary
The dataset underwent multiple cleaning steps to ensure consistency and usability:

1) Missing values in the postal_code field were filled with -1.
2) Duplicate records were removed to ensure data integrity.
3) Text fields (e.g., customer_name, city) were standardized to lowercase and trimmed of whitespace.
4) Date columns (order_date, ship_date) were converted to the dd-mm-yyyy format using datetime types.
5) Column names were renamed to be lowercase, with underscores instead of spaces for uniformity.
6) Data types were validated and corrected (e.g., postal codes as int, dates as datetime).
