# data_cleaning_with_pandas_and_pyspark-


The Data Engineers of a particular company often keep logs of the details of previously executed pipelines triggered by their orchestration tool (or
sometimes, manually).
A new Engineering Manager has been hired and will need to know and understand the functions and processes carried out as documented in the log
file.
You are to help this individual clean and transform the data found in the log file (with any methods or tools of your choice), and perform some analyses
you think will be helpful to the Manager.
Files Provided:
log.txt - contains all of the tasks logged by the Data Engineering team
columns.txt - the corresponding headers of the dataset existing in the log file (in the same order) including some other necessary details


# Tools
- Pandas
- Pyspark

# Cleaning and transformation tasks
## issues
- set trackerId as index
- split state and country
- change timestamp from unix to datetime 
- check failed operations
- convert to csv format
- partition the file 
- run business analysis on data

