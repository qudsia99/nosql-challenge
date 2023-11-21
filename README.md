# nosql-challenge

## Establishments Aggregation via MongoDB, on jupyternotebook

##### This file aggregates a data with over 35,000 documents of establishment data of businesses, including their rating scores, geographical information, business types, and more sub values. 

##### The 'setup_starter.ipynb' file, imports the JSON file into the mongoDB database, inside a new collection called 'establishments'. A new restaurant is added into the collection and updated, followed by queries ran to see how many establishments have a local authority name of "Dover", and those are wiped from the collection due to irrelevance. Data type is also converted for 'longitude' and 'latitude', from string to decimal, in order to ensure credible querying via geocoding in the following file 'analysis_starter.ipynb'.

##### The next file ('analysis_starter.ipynb') contains a more rigorous analysis, where unique establishments are queried, by hygiene scores, rating value, groupped by authority name and queried by longitude and latitude, with a degree range of 0.01. All queries are inserted into seperate pandas dataframes, in order to view filtered data in a unique table. 

###### Please note, line by line code broken down inside respective .ipynb files.
