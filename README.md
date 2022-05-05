# SeeDB
In this project, we implemented some of the work done in the "SEEDB: Supporting Visual Analytics with Data-Driven Recommendations" paper.
The code is mainly contained in the two notebook files SeeDB.ipynb and DataCleaning.ipynb.

## DataCleaning.ipynb:
This file contains the code that we used to clean the version of the Census dataset we had. 
It accesses the adultdata_dirty.csv file and generates the clean dataset file adultdata.csv.

## SeeDB.ipynb:
This is the main code file. It contains all the implemented algorithms. 
It starts with the code used to generate the database. We used SQLite to generate and deal with the database. SQLite generates a .db file for the database it generates. 
You don't need to download or install anything to generate the database. Just run the first 3 cells in the notebook.

## adultdata.csv
This file contains the clean data that we work on in SeeDB.ipynb.

## adult_data.csv
This is the file downloaded from https://archive.ics.uci.edu/ml/datasets/Census+Income 



