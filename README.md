# Customer_Train

Storing data efficiently

DataFrame: ds_jobs_transformed
Data: customer_train.csv

Requirements:
* Columns containing categories with only two factors must be stored as Booleans (bool).
* Columns containing integers only must be stored as 32-bit integers (int32).
* Columns containing floats must be stored as 16-bit floats (float16).
* Columns containing nominal categorical data must be stored as the category data type.
* Columns containing ordinal categorical data must be stored as ordered categories, and not mapped to numerical values, with an order that reflects the natural order of the column.
* The DataFrame should be filtered to only contain students with 10 or more years of experience at companies with at least 1000 employees, as their recruiter base is suited to more experienced professionals at enterprise companies.
