README.md for scrubbing.

We will be using the (OSEMN) framework for this project. OSEMN is an acronym for Obtaining, Scrubbing, Exploring, Modeling and Interpretation.

In this project data collected was cleaned, below you’ll find the data that was provided. The data includes sales numbers for Inu + Neko over a 6-month period. The data are in good shape, however, not perfect. It is upon this premise that a series of actions were taken to clean the data.

The source data given have issues with missing data, inconsistencies in the different state names, incorrect values for the “sales_total” column, and at least one duplicate (the 5th row).

This was done by dropping the column with too many missing values, fixing inconsistencies with the state names (replace abbreviations), calculating the correct values for “sales_total” using the “prod_price” & “trans_quantity” columns, and removing duplicate rows (keeping the first instance).

From the source data, we were required to answer the questions enumerated below 
1.	Determine how many duplicate records are there.
2.	Remove any duplicate records found in the full rows.
3.	Fix inconsistencies in the column cust_state.
4.	Correct the values in total_sales column (prod_price *trans_quantity).
5.	Validate the price in prod_price. Remove any rows that are obviously wrong.
6.	How many missing values are there?
7.	Drop the column with missing values
Click here for the source data.

