---
title: "CodeBook.md"
author: "Saptarshi Lahiri"
date: "19 March 2017"
output: html_document
---

## Code Book For Getting & Cleaning Data
# By Saptarshi Lahiri

- Deployer library loaded
- All code objects go below

- x_train 
- y_train 
- subject_train 
- x_test 
- y_test 
- subject_test 
- features 
- activityLabels
- mrg_train
- mrg_test
- setAllInOne
- colNames
- mean_and_std
- setForMeanAndStd
- setWithActivityNames
- secTidySet 
- secTidySet 

- Definitions
-- Arithmetic mean and standard deviation are calculated using existing R function
- As given in the problem statement, the code itself
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
