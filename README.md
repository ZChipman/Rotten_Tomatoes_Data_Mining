# Rotten_Tomatoes_Data_Mining

## Introduction:
Used Association Rules Mining and classification techniques such as SVM to predict the critical reception of films, using a Kaggle data set containing nearly, 10,000+ films. This originally was the final project for Applied Machine Learning course at Syrcuse University. 

## Files:

Original_Report: This document was the final report for the orgiinal project.

Original.Rmd: This was the R markdown file used to create the final report document. R studio will be required to view this file. 

rotten_tomatoes_movies.csv: CSV file containing the Kaggle data set.

## Technical Specifications:

The original code was written using R (version 4.0.3) and RStudio. Future work will be written in Python using Jupyter notebook. Is should be noted that the Association Rules mining code will not be converted as I would like to focus of future research to be on the classification models. 

## Development:

### Data Cleaning:
The original data set had 17,712 observations of 22 variables. After removing unwanted rows and columns, the data set had 15,814 observations of 13 variables.

### Exploratory Data Analysis:

<img width="1280" alt="Status Chart" src="https://user-images.githubusercontent.com/87530934/235267901-3270a792-15f1-487a-a10a-3140cdc1f011.png">

## Future Goals:

### Transfer to Python:
Although the original project was conducted in R, future analysis will be conducted in Python. This is because Python has more versatility when it comes to machine learning and natural language processing.

### Experiment with New Models:
Since I first worked on this project, I have gained experience in various other machine learning techniques (including Neural Networks). Therefore, I plan to implement these models on the current data and analyze the results.

### Optimization of Existing Models:
One of the goals of the original project was to compare the performance of various models. Through the optimization of these models, I plan on obtaining further insights on which of these models works best with the data. 

### Implement Natural Language Processing:
The dataset also contained two text columns: Info (a summary of the film) and Consensus (the critical consensus of the film). In the original project, time constraints did not allow me to implement this data into the project. In the future, I plan to either implement the text as a separate model or as part of one of the existing models.

Rferences:

https://www.kaggle.com/datasets/stefanoleone992/rotten-tomatoes-movies-and-critic-reviews-dataset
