# coursera-getting-and-cleaning-data-peer-assessment

What is this?
This is a repository with the code for the peer assesment required on the Coursera course Getting and Cleaning Data

What is the data
The data used on this script can be found here.

The data is on a folder called UCI HAR Dataset, we will only need the following files:

activity_labels.txt
features.txt
subject_test.txt
subject_train.txt
X_test.txt
X_train.txt
y_test.txt
y_train.txt
For the script to work you need to put the UCI HAR Dataset on your R working directory.

The code
This project has only one script run_analysis.R. This code turns all the files above on a tidy dataset, by doing the following:

Merges the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement.
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive activity names.
Creates a independent tidy data set which is called tidy.cs vwith the average of each variable for each activity and each subject.
Detailed information about generated datasets can be found on the CodeBook.md file.
