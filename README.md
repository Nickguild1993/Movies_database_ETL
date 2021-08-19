# Movies-ETL
Extract, Transform and Load
# Overview of Module 

The purpose of this analysis was to create an easily accessible database for the "Hackathon" participants to parse through.   We had three different CSV files that we had to ETL (extract, transform and load) that each had data that needed to be cleaned to a varying degree.  Once we extracted and transformed the data, we used the python function **to_sql()** to load those datasets into tables in SQL. 

In order to clean the data, we used tools like *regular expressions* to "pattern match" strings and replace those values, merged columns to combine similiar data, as well as outright dropping columns that were either too disorganized and dirty or didn't contain enough values across the thousands of rows to justify having so many NaNs present.  

There were many challenging aspects of this module, starting with the sheer amount of data in those CSV files that had to be parsed, in addition to the less than ideal cleanliness of the wikipedia dataset, and then getting used to utilizing new tools like the regular expressions mentinoed above.

Now that the datasets are in SQL tables, the participants of the "Hackathon" will be able to access and analyze the data easily because of the homogenized structure and cleaning we installed during the transofrm phase.  Hopefully they have a good time, as this module was the most time consuming and challenging to date.
