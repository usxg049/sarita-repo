				Code Book For Getting Cleaning Data Course Project

The purpose of this code book is to provide information on data set on Human Activity Recognition Using Smartphones.
The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone.
The goal is to prepare tidy data that can be used for later analysis.

Data set loaded from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip.

UCI HAR DataSet.zip file is loaded.

The dataset includes the following files:
=========================================

- 'README.txt'

- 'features_info.txt': Shows information about the variables used on the feature vector.

- 'features.txt': List of all features.

- 'activity_labels.txt': Links the class labels with their activity name.

- 'train/X_train.txt': Training set.

- 'train/y_train.txt': Training labels.

- 'test/X_test.txt': Test set.

- 'test/y_test.txt': Test labels.

- Features are normalized and bounded within [-1,1].
- Each feature vector is a row on the text file.

Activities:

1	WALKING
2	WALKING_UPSTAIRS
3	WALKING_DOWNSTAIRS
4	SITTING
5	STANDING
6	LAYING

Features:

2 variables and # of observationa (561)

Following steps to prepare tidy data:

1.  Get data using fileurl
2.  Unzip data files
3.  Read data files
4.  Merge all that data into one data set
5.  Name the measurement columns after the feature names, and give names to the id 
6.  Create a new data frame whose measurement columns contain only mean and st. dev features
7.  Trim the rows to the 180 needed to show mean values for each subject-activity pair
8.  Rename and output the data to "Samsung_Data.txt"



