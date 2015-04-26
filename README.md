Goal

The goal of the run_analysis.R script is to accomplish the following.

Merges the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement.
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive variable names.
From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

Procedure

Read data from raw text files into data frames (data assumed to be downloaded prior to script execution)
Merge test and train subject data.
Merge test and train y data. Merge resulting y data with activity labels.
Merge test and train x data. Apply feature data as feature names.
Combine merged subject, x and y data (results from 2,3,4).
Subset to only mean & stdv features.
Compute means grouped by subject and activity.
Write results to the tiny_data_set_with_the_averages.txt file.
