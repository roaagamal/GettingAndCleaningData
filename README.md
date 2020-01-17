# GettingAndCleaningData

Coursera 'Getting and Cleaning Data' Course Project (Week 4).
This repository contains the R code (run_analysis.R), a tidy dataset that is the output of the code (new_tidy_dataset_sum), the code book (CodeBook.md) and the ReadMe.md file for the Coursera 'Getting and Cleaning Data' Course project.

The data
The original dataset was collected with the Samsung Galaxy S smartphone. Using its embedded accelerometer and gyroscope, 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz was captured. The data originates from the UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Files
This repository contains the following files:

Code - run_analysis.R
The code written for this project uses the original dataset and does the following:

Merges the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement.
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive variable names.
From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
New Dataset - new_tidy_dataset.txt
The new dataset it the output of the abovementioned steps performed by the code.

Code Book - CodeBook.md
The Code book describes the variables, the data, and all transformations or work that was performed to clean up the data.
