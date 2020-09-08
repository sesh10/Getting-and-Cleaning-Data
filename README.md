# Getting-and-Cleaning-Data

Peer-graded Assignment: Getting and Cleaning Data Course Project
This repository is a Nunno Nugroho submission for Getting and Cleaning Data course project. It has the instructions on how to run analysis on Human Activity recognition dataset.

### Dataset:
Human Activity Recognition Using Smartphones

### Files:
CodeBook.md a code book that describes the variables, the data, and any transformations or work that I performed to clean up the data

### run_analysis.R:
Performs the data preparation and then followed by the 5 steps required as described in the course project’s definition:
* MergeData merges the training and the test sets to create one data set.
* TidyData extracts only the measurements on the mean and standard deviation for each measurement from MergeData.
* Uses descriptive activity names to name the activities in the data set
* names() is used to appropriately label the data set with descriptive variable names.
* FinalData is the independent tidy data set with the average of each variable for each activity and each subject. It is taken from TidyData.


FinalData.txt is the exported final data after going through all the sequences described above.
