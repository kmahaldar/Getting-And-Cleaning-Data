Getting-And-Cleaning-Data
=========================

This is a project assignment of "Getting and Cleaning Data" course


### Overview
This project serves to demonstrate the collection and cleaning of a tidy data set that can be used for subsequent
analysis. 


###  Data description

The source data for this project is found here.
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

The  A full description is available at the site where the data was obtained:
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 

Please download the zip and extract in your R workspace

###  R Script to get and clean data

The script  run_analysis.R, does the following operations 

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names. 
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 

###  Execution of the R Script to get and clean data

   1. Download data : dowbnload the zip file from the given URL , extract it in your workspace. Your workspace should have the folder "UCI HAR Dataset" and all data files inside it. If you want to change the name of the folder then corresponding modification have to be done in the script.
   
   2. Download and execute script : copy run_analysis.R is your workspace and run the command -    source("./run_analysis.R") . It should create a file "tidy_data.txt" in your workspace.

### Additional Information
Additional information about the variables, data and processes can be found in the CodeBook.MD file.
