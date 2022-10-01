# ETL-pipeline-for-Disaster-Response-
The ETL pipeliine will classify the messages received during a disaster according to the kind of issue. It will increase response velocity of Disaster repsonse team to handle scenarios

The project is developed in two phases:

Phase 1:
ETL pipeline is created for doing data preprocessing and modelling
> Loads data of  messages and categories
> Merges the data on join
> Cleans the data
> Storing the data in SQlite database

ETL is stored in process_run.py
The notebook is stored in ETL.ipynb

Phase 2:
> Loads the data from Sqlite database
> Splits the data into trainig and testing dataset
> Builds a text processing, NLP pipeline
> Exports the model in a pickle file

ML pipeline is stored in train_classifier.py
The notebook is stored in ML.iypnb

-- Thanks to Udacity for the project
