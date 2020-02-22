## ETL Project

### Lake Michigan E-coli Effects on Chicago Restaurant Safety

###One of our datasets was too large to upload to Github so it can be found here: https://www.kaggle.com/chicago/chi-restaurant-inspections

Our team's goal for this ETL assignment is to connect a csv dataset found on kaggle which recorded the daily ecoli levels found at beaches in Chicago with another csv kaggle dataset recording failed Chicago restaurant inspections by date. Our assumption is that there is a correlation between poor water quality and restaurant health issues.

Per the project specifications, our tasks are as follows:

* **Extraction**

  * Put each CSV into a pandas DataFrame.

* **Transform**

  * Clean the data sets in pandas by dropping, renaming and removing null values from pertinent columns

  * Reformat the date columns to be in proper datetime format for SQL and to match eachother to act as the Primary Key

* **Load**

  * Create a connection to database.

  * Check for a successful connection to the database and confirm that the tables have been created.

  * Append DataFrames to tables. Be sure to use the index set earlier.

If continuing with our set, a user could potentially add on to this project by scraping Yelp for restaurant reviews by date to find correlations with reviews referencing illness or e-coli with high e-coli levels in lake water.

