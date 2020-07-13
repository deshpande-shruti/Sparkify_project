# Sparkify_Capstone_project
Udacity Capstone project

## Motivation
1. Load large dataset into Spark and manipulate them using Spark SQL and Spark Dataframes.
2. Use the Machine Learning API's within Spark ML to build and tune models.
3. Integrating the skills I have learned in the Spark course and the Data Scientist Nanodegree program.

## Aim of the project
The project aims to predict the churned users based on activities and attributes data of them. And deploy the solution on a distributed system. Original size of the datasets is 12GB. Due to limited computation power of free version of IBM cloud, a medium sized sub-dataset is utitized.

## Expected Results
At the end of this project, a model for churn prediction should have been created and evaluated. The model should have been trained and tested on a subset of the 12GB of data, and the final testing should happen on completely separate validation set. 

## Framework needed to run this jupyter notebook:
- Pyspark SQL and Pyspark ML and other libraries its building on
- Matplotlib for visualization 
- IBM Cloud or other cloud services.
- Python 3.5

## Overview of the files

README.md - This readme

[Sparkify.ipnby](https://github.com/deshpande-shruti/Sparkify_Capstone_project) : The notebook used from Udacity Workspace.

## Improvement
To achieve the optimal user experience, using more capable hardware and moving the text extraction process from the cloud to the device would be essential. This would reduce the processing time and give access to the outputs of all of the modules of the text extraction pipeline, which would, in turn, enable the following features:

- User-guided reading (e.g. read big text first, or read the text the user is pointing at)

- Output filtering (e.g. ignore text smaller than some adjustable threshold)

- Passive text detection (auditory cue on text detection, perhaps with additional information encoded in the tone and volume)

## Summary of Project
Procedures of analysis:  
1. data cleaning
2. data exploration
3. feature engineering
4. modelling
5. deploy on IBM cloud

## Blog post
[Sparkify blog](https://medium.com/@sonyand96/churn-analysis-on-a-huge-dataset-861a8e7c8c25)


## Acknowledgement
The dataset is kindly provided by Udacity team. And some instructions in the notebook are also well prepared by Udacity team.

## References
For this project, the course material at Udacity has been used for reference. On top of that, the official pySpark documentation has also been used ( https://spark.apache.org/docs/latest/api/python/index.html )
