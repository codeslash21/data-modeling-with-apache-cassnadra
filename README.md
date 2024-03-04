# Overview
Built an ETL(Extract, Transform, Load) pipeline that transfers data from a set of CSV files within a directory to create a streamlined CSV file to model and insert data into Apache Cassandra tables. Created different cassandra data models optimized for different queries those we needed to execute.

## Files
- **`event_data`** This folder contains all the `csv` files, these are the source of ETL pipelinne. All the data was provided by Udacity
- `event_datafile_new.csv` This is the output file of ETL pipeline. This file is used to model and insert data into Apache Cassandra tables.
- `Project_1B_ Project_Template.ipynb` has the code for ETL and Cassandra data modeling


## Tools and Packages
### Tools
- Apache Cassandra
- CQL
- Python
- Jupyter NoteBook

### Python Packages
- cassandra
- os
- glob
- csv
- prettytable

## Project Steps
- **ETL:** Build an ETL pipeline that transform data from a set of CSV files within a directory to create a streamlined CSV file that can be used to model and insert data into Apache Cassandra tables.
- **Data Modeling:** Based on ETL output file and the queries we need to run model different Apache Cassandra data model those will be optimized and give exepected output. Main important thing is choosing `Partition Key` and `Clustering Columns` properly so that data will be evenly distributed and appropriate rows will be fetched for the executed query.
