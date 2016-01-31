# Getting-and-cleaning-data-assignment
Repository for the Getting and Cleaning data assignment

title: "README.MD"
author: "W Fuller"
date: "January 31, 2016"
---
Getting and Cleaning Data
Course Project

Created an R script called run_analysis.R that does the following.

Merge the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement.
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive activity names.
Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

Steps used to work on project

Downloaded the data source https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip and unzip in local working directory on local drive. After unzipping it creates a UCI HAR Dataset folder.
Put run_analysis.R in the parent folder of UCI HAR Dataset, then set it as your working directory using setwd() function in RStudio.
Run source("run_analysis.R"), then it will generate a new file tidy_data.txt in your working directory.

Dependencies

run_analysis.R file will help you to install the dependencies automatically. It depends on reshape2 and data.table.
