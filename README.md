# GettingAndCleaningData
Getting and Cleaning Data Course Project

Author : Julie Ann Salido (https://github.com/jasalido/GettingAndCleaningData)

This is the course project for the Getting and Cleaning Data Coursera course. The goal is to 1) a tidy data set as described below, 2) a link to a Github repository with your script for performing the analysis, and 3) a code book that describes the variables, the data, and any transformations or work that you performed to clean up the data called CodeBook.md. 

The R script, run_analysis.R, does the following:

1. Download  and unzipped the dataset if it does not already exist in the working directory. 
  The full description is available at the site where the data was obtained:
  http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
  
  The dataset for the project:
  https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

2. Merging the training and the test sets to create one data set.
3. Extracting only the measurements on the mean and standard deviation for each measurement.
4. Using descriptive activity names to name the activities in the data set.
5. Appropriately labeling the data set with descriptive variable names.
6. Creating an independent tidy data set with the average of each variable for each activity and each subject.
