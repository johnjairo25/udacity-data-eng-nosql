# Data modeling project with Cassandra

This repository contains the solution to the second project of the Udacity's Data Engineering NanoDegree.   

The project consists of migrating data from CSV files to Cassandra. The data is moved according to 
the requirements specified in the Jupyter Notebook.   

The `Project_1B_ Project_Template.ipynb` file is a Jupyter Notebook that does the following:

- Reads all the CSV files from the `event_data` folder and merges them into 
the `event_datafile_new.csv` file.
- Creates the `sparkify` keyspace in Cassandra.
- Creates three tables, one for each one of the requirements specified in the notebook.

## Running the project

To run the project, Jupyter Notebook is required. The easiest way to install Jupyter Notebook is 
with [Ananconda](https://www.anaconda.com/).

Just open the `Project_1B_ Project_Template.ipynb` file with Jupyter Notebook and run each one 
of the cells.

