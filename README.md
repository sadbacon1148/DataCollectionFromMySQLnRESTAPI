# Data Engineering Mini Project

This repository contains a mini project focusing on data engineering tasks, including querying a database, converting data to pandas dataframes, retrieving currency conversion data from a REST API, and extracting date information from a column for data integration.

## Overview

The project involves the following steps:

1. **Installation**: Install PyMySQL to establish a connection with the database.

2. **Configuration**: Configure the database credentials to access the desired database.

3. **Connecting to the Database**: Establish a connection with the database using the provided connection code.

4. **Listing Tables**: Retrieve a list of tables available in the database.

5. **Querying Data**: Query data from a table to preview its contents, including row counts and data types.

6. **Converting to Pandas**: Convert the queried data into pandas dataframes for easier manipulation and analysis.

7. **Data Retrieval from REST API**: Use the request library to retrieve data from a REST API, specifically for currency conversion from GBP to THB.

8. **Data Transformation**: Convert the retrieved data into JSON format, which can be easily converted into a dataframe for further processing.

9. **Date Extraction**: Extract the date information from the InvoiceTimestamp column to facilitate data integration and joining with the currency dataframe.
