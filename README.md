Peer-Graded-Assignment:Getting and Cleaning Data


This repository is my(Prem B. Thapa)submission for Getting and cleaning  data assignment and provides instructions to perform analysis on the Human Activity Recognition Dataset.



The link for the dataset:https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
download it into your working directory using the download.file()



The files in this repo include:


Codebook.md<-a code book that describes the variables, the data, and any transformations or work that I performed to clean up the data.

run_analysis.R performs the data preparation and then followed by the 5 steps required as described in the course project’s definition:
Merges the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement.
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive variable names.
From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.


FinalData.txt is the exported final data after going through all the sequences described above.
