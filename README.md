# DMA-Final

Data Mining and Analysis Final Project
Nathan Matheis, Nathanael Johnson & Jeffrey Kendig

Dataset Link:
https://data.cdc.gov/Case-Surveillance/COVID-19-Case-Surveillance-Public-Use-Data/vbim-akqf

Files Include:

covid_data_cleaner.ipynb
    Removes all rows with missing data and removes unwanted columns for the given initial dataset

covid_cleaned.csv
    Cleaned version of the original dataset created by covid_data_cleaner.ipynb

covid_kmeans.ipynb
    Performs a k-means analysis on the covid_cleaned.csv file, producing a scatterplot with clusters

covid_knn.ipynb
    Performs a k nearest neighbors analysis on the covid_cleaned.csv file, producing a confusion 
    matrix and a classification report

Covid_Naive_Baise.ipynb
    Performs a Naive Bayes analysis on the covid_cleaned.csv file, producing a prediction on if a 
    given individual will survive contgracting covid

Covid_visualize.ipynb
    Produces varius charts and figures based on the data provided by the covid_cleaned.csv file
Footer
© 2022 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
Docs
