#Getting And Cleaning Data - Course Project

Author: Chinta Patanjali

This repository contains the R-code and documentation files for the 
Course Project of "Getting and Cleaning Data" on Coursera.

##Overview
The purpose of this project is to demonstrate our ability to collect,
work with, and clean a data set. The goal is to prepare tidy data that 
can be used for later analysis.

This project requires submission of:
1. a tidy data set, 
2. a link to a Github repository with the script for performing the 
   analysis, 
3. a code book that describes the variables, the data, and any 
   transformations or work that you performed to clean up the data 
   called CodeBook.md.
4. a README.md file that explains how all of the scripts work and how 
   they are connected.

The dataset for this project is:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

The script for performing the analysis (in step 2) is run_analysis.R. It does the following:

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set.
4. Appropriately labels the data set with descriptive variable names. 
5. From the data set in step 4, creates a second, independent tidy data set with the average 
   of each variable for each activity and each subject.

##Modification to reproduce the project

After unzipping the source files, you will need to make one modification to the R file before 
you can process the data.
    *Note that on line 26 of run_analysis.R, you will set the path of the working directory to 
     the location where the UCI HAR Dataset was unzipped.
(for me it was C:/Users/Patanjali/Documents/GitHub/Getting And Cleaning Data Course Project/UCI HAR Dataset)

##Output Files

1. Tidy data set file: averages_data.txt
2. File that describes the variables, the data, and any transformations or work that was performed to clean up the data: CodeBook.md