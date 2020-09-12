Description of Data and its variables .

source:http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones


Data Set Information:

The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. 
Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. 
The experiments have been video-recorded to label the data manually.
The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data.


The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window).
The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used.
From each window, a vector of features was obtained by calculating variables from the time and frequency domain.



The final summary tidy dataset "tidydata.txt" contains the average of each variable for each activity and each subject from the Human Activity Recognition Using Smartphones Data Set.

The data has been collected on individuals performing 6 type of tasks.
1.WALKING

2.WALKING_UPSTAIRS

3.WALKING_DOWNSTAIRS

4.SITTING

5.STANDING

6.LAYING

STEPS FOR PROCESSING DATA 

1 : download dataset from given link and extract at your working directory
2:load it into Rstudio and assign data to variables
features <- features.txt 

activities <- activity_labels.txt 

subject_test <- test/subject_test.txt

x_test <- test/X_test.txt 

y_test <- test/y_test.txt : 

subject_train <- test/subject_train.txt 

x_train <- test/X_train.txt 

y_train <- test/y_train.txt 

Merge the datasets together  to create a single dataset  & extract the mean and standard deviations for each measurement .

Label dataset with appropriate variables & create a second, independent tidy data set with the average of each variable for each activity and each subject
