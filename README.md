# Peer-graded Assignment: Getting and Cleaning Data

This is my submission for Peer Graded Assignment: Getting and Cleaning Data Course Project.

## Dataset

Data for this project was obtain from the Coursera assignment instructions. Data represent data collected from the accelerometers from the Samsung Galaxy S smartphone. The data for the project can be obtained via the link below:

[https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip]

## Files

- CodeBook.md  a code book that modifies and updates the available codebooks with the data to indicate all the variables and summaries calculated, along with units, and any other relevant information

- run_analysis.R performs the data preparation and then followed by the 5 steps required as described in the course project’s definition:
  1. Merges the training and the test sets to create one data set.
  2. Extracts only the measurements on the mean and standard deviation for each measurement.
  3. Uses descriptive activity names to name the activities in the data set
  4. Appropriately labels the data set with descriptive variable names.
  5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

- TidyData.txt is the exported final data after going through all the sequences described above.
