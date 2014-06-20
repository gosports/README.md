
README.md

Summary:
========
The purpose of this project is to collect, work with, and clean a data set. The goal is to prepare a tidy data that can be used for later analysis.

The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. It was collected by Anguita et al. (2012). A full description is available at the site where the data was obtained: 
  
  http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 

Here are the data used for the project: 
  
  https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 


run_analysis.R script creates a tidy data set as following:
============================================================
- Merging the training and the test sets to create one data set.
- Extracting only the measurements on the mean and standard deviation for each measurement. 
- Using descriptive activity names to name the activities in the data set
- Appropriately labeling the data set with descriptive variable names. 
- Creating a second, independent tidy data set (average_variable_activity_subject.txt) with the average of each variable for each activity and each subject. 


Codebook:
=========
  CodeBook.md repo has further information on data.
