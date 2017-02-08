
#### More SQL

  * Imports
  * Aggregates
  * Group by

#### Assignments for Feb. 14

  * Reading: [Introducing Treasury.io](https://source.opennews.org/articles/introducing-treasuryio/)

  * SQL: Using your existing campaign_finance.sqlite file, download this CSV file of expenditures by the Senate campaign of Josh Mandel. Import it, creating a table called mandel. Look at the CSV file in Excel before you define the fields in SQLite – be sure to define the zip field as VARCHAR, not INTEGER. Define the amount, month, day and year fields as INTEGER.

  Once you've done that, write queries to do the following, using wildcards (but not always) and GROUP BY:

  1. Show the total amount of money spent in each state.
  2. Show the total amount for each purpose, with the largest amount first.
  3. Show the total amount of any expenditures related to direct mail.
  4. Show the total amount spent for each month and year, with the largest amount first
  5. Show the recipients and total amounts for Payroll expenses, but not payroll taxes or fees.

  Save your queries in a file called mandel.txt and upload that and your .sqlite file to GitHub.
