## Code Book
This code book summarizes the dataset and resulting data fields in TidySet.txt.

## About dataset
As sourse data for work was used Human Activity Recognition Using Smartphones Data Set. 
A full description is available at the site where the data was obtained: 
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 

Here are the data for the project: 
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip


## About run_analysis.R script
File with R code "run_analysis.R" perform 5 following steps (in accordance assigned task of course work):
1. Downloading and unzipping dataset

2. Merging the training and the test sets to create one data set.

    2.1 Reading files

      2.1.1 Reading trainings tables

      2.1.2 Reading testing tables

      2.1.3 Reading feature vector

      2.1.4 Reading activity labels

    2.2 Assigning column names

    2.3 Merging all data in one set

3. Extracting only the measurements on the mean and standard deviation for each measurement

    3.1 Reading column names

    3.2 Create vector for defining ID, mean and standard deviation

    3.3 Making nessesary subset from setAllInOne

4. Using descriptive activity names to name the activities in the data set

5. Appropriately labeling the data set with descriptive variable names

6. Creating an independent tidy data set with the average of each variable for each activity and each subject.

## About the variables
1. x_train , contains the dataset of X_train.txt with 7352 samples x 561 features.
2. y_train , contains the dataset of y_train.txt with 7352 samples x 561 features.
3. x_test , contains the dataset of X_test.txt with 2947 samples x 561 features.
4. y_test , contains the dataset of y_test.txt with 2947 samples x 561 features.
5. subject_train, contains subject id of the individual samples for training.
6. subject_test, contains subject id of the individual samples for testing.
7. features, contains the dataset of 561 features taken.
8. activityLabels, contains the dateset vector number for all 6 activities.
