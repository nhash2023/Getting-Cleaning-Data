#This Codebook shows how the available data is download, merged and created into the tidy_data.txt

## About the data downloaded:
The source data are from the Human Activity Recognition Using Smartphones Data Set. Here are the data for the project: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

## About the R script code:
1. Readind and Merging the training and the test sets to create one data set.
      1.1 Download the file and put the file in the data folder and unzip file
      1.2 Get list of files from the unzipped files located in the folderUCI HAR Dataset
      1.3 Read data from the files into the variables
      1.4 Concatenate the data tables by rows
      1.5 set names to variables
      1.6 Merge columns to get the data frame Data for all data
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
      2.1 Subset Name of Features by measurements on the mean and standard deviation
      2.2 Subset the data frame Data by seleted names of Features and see structure of the data
3. Using descriptive activity names to name the activities in the data set
4. Labeling the data set with descriptive and appropriate variable names. 
5. Creating a second, independent tidy data set with the average of each variable for each activity and each subject.
      5.1 create independent tidy data set with the average of each variable for each activity and each subject
      5.2 save this tidy data into file text named tidy_data.txt

This code assumes that all the data present is in the same folder, without names altered.

## Variables:
