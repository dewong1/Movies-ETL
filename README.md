# Movies-ETL
Use the Extract, Transform, Load (ETL) process to create data pipelines (wikipedia & kaggle) to prepare for a hackathon. 

## Overview of Project

Analysis is impossible without access to good data, so creating data pipelines is often the first step before any analysis can be performed. We gathered movie and ratings data from both Wikipedia and Kaggle, combined then, and saved them into a SQL database so that the hackathon participants have a nice, clean, dataset to use. In data analysis, a hackathon is an event where teams of analysts collaborate to work intensively on a project, using data to solve a problem. Hackathons generally last several days, and teams work around the clock on their projects. To create clean movie data, we followed the **ETL** process: **extract** the Wikipedia and Kaggle data from their respective files, **transform** the datasets by cleaning them up and joining them together, and **load** the cleaned dataset into a SQL database.

### Purpose and Background

The purpose of this project was to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. We refactored the original Wikipedia-Kaggle-ETL code to create one function that takes in the three files— *Wikipedia data*, *Kaggle metadata*, and the *MovieLens rating data*— and performs the ETL process by adding the data to a PostgreSQL database.

