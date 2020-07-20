This is the code book for "Run_Analysis.R" which will be followed by the 5 steps required as described in the course project’s definition.

1. Merging the training and the test sets to create one data set.
2. Extracting only the measurements on the mean and standard deviation for each measurement.
3. Using descriptive activity names to name the activities in the data set
4. Appropriately labeling the data set with descriptive activity names.
5. Creating a second, independent tidy data set with the average of each variable for each activity and each subject.

## Variables description
  -	features <- features.txt 
  The features selected for this database come from the accelerometer and gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ.
	
  - activities <- activity_labels.txt 
	List of activities performed when the corresponding measurements were taken and its codes (labels)
  
  - x_train <- test/X_train.txt 
	contains recorded features train data
	
  - y_train <- test/y_train.txt 
	contains train data of activities’code labels
 	
  - subject_train <- test/subject_train.txt 
	contains train data of 21/30 volunteer subjects being observed
	
  - subject_test <- test/subject_test.txt 
	contains test data of 9/30 volunteer test subjects being observed
	
  - x_test <- test/X_test.txt 
	contains recorded features test data
	
  - y_test <- test/y_test.txt 
	contains test data of activities’code labels

## Processing variables
  -	Subject is created by merging subject_train and subject_test 
   
  - X is created by merging x_train and x_test 
	
  -	Y is created by merging y_train and y_test 
	
  -	Merged_Data is created by merging Subject, Y and X 
  
  - TidyData is created by subsetting Merged_Data, selecting only columns: subject, code and the measurements on the mean and standard deviation (std) for each measurement
 
  
