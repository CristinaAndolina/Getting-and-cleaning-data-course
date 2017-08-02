# Getting and cleaning data course project
One of the most exciting areas in all of data science right now is wearable computing - see for example this article. Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most advanced algorithms to attract new users. The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone.

# How the script works
The script is divided in the following five sections according to the project instructions:
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

# Code book

## Key columns
### Variable | name	Description
activity_name	| Label of activity, Factor w/ 6 levels
subject	| ID of subject, int (1-30)

## Non-key columns
### Variable | name	Description
tBodyAcc-mean()-X	| the average value for this feature, num (range: -1:1)

tBodyAcc-mean()-Y	| the average value for this feature, num (range: -1:1)

tBodyAcc-mean()-Z	| the average value for this feature, num (range: -1:1)

tBodyAcc-std()-X	| the average value for this feature, num (range: -1:1)

tBodyAcc-std()-Y	| the average value for this feature, num (range: -1:1)

tBodyAcc-std()-Z	| the average value for this feature, num (range: -1:1)

tGravityAcc-mean()-X	| the average value for this feature, num (range: -1:1)

tGravityAcc-mean()-Y	| the average value for this feature, num (range: -1:1)

tGravityAcc-mean()-Z	| the average value for this feature, num (range: -1:1)

tGravityAcc-std()-X	| the average value for this feature, num (range: -1:1)

tGravityAcc-std()-Y	| the average value for this feature, num (range: -1:1)

tGravityAcc-std()-Z	| the average value for this feature, num (range: -1:1)

tBodyAccJerk-mean()-X	| the average value for this feature, num (range: -1:1)

tBodyAccJerk-mean()-Y	| the average value for this feature, num (range: -1:1)

tBodyAccJerk-mean()-Z	| the average value for this feature, num (range: -1:1)

tBodyAccJerk-std()-X	| the average value for this feature, num (range: -1:1)

tBodyAccJerk-std()-Y	| the average value for this feature, num (range: -1:1)

tBodyAccJerk-std()-Z	| the average value for this feature, num (range: -1:1)

tBodyGyro-mean()-X	| the average value for this feature, num (range: -1:1)

tBodyGyro-mean()-Y	| the average value for this feature, num (range: -1:1)

tBodyGyro-mean()-Z	| the average value for this feature, num (range: -1:1)

tBodyGyro-std()-X	| the average value for this feature, num (range: -1:1)

tBodyGyro-std()-Y	| the average value for this feature, num (range: -1:1)

tBodyGyro-std()-Z	| the average value for this feature, num (range: -1:1)

tBodyGyroJerk-mean()-X	| the average value for this feature, num (range: -1:1)

tBodyGyroJerk-mean()-Y	| the average value for this feature, num (range: -1:1)

tBodyGyroJerk-mean()-Z	| the average value for this feature, num (range: -1:1)

tBodyGyroJerk-std()-X	| the average value for this feature, num (range: -1:1)

tBodyGyroJerk-std()-Y	| the average value for this feature, num (range: -1:1)

tBodyGyroJerk-std()-Z	| the average value for this feature, num (range: -1:1)

tBodyAccMag-mean()	| the average value for this feature, num (range: -1:1)

tBodyAccMag-std()	| the average value for this feature, num (range: -1:1)

tGravityAccMag-mean()	| the average value for this feature, num (range: -1:1)

tGravityAccMag-std()	| the average value for this feature, num (range: -1:1)

tBodyAccJerkMag-mean()	| the average value for this feature, num (range: -1:1)

tBodyAccJerkMag-std()	| the average value for this feature, num (range: -1:1)

tBodyGyroMag-mean()	| the average value for this feature, num (range: -1:1)

tBodyGyroMag-std()	| the average value for this feature, num (range: -1:1)

tBodyGyroJerkMag-mean()	| the average value for this feature, num (range: -1:1)

tBodyGyroJerkMag-std()	| the average value for this feature, num (range: -1:1)

fBodyAcc-mean()-X	| the average value for this feature, num (range: -1:1)

fBodyAcc-mean()-Y	| the average value for this feature, num (range: -1:1)

fBodyAcc-mean()-Z	| the average value for this feature, num (range: -1:1)

fBodyAcc-std()-X	| the average value for this feature, num (range: -1:1)

fBodyAcc-std()-Y	| the average value for this feature, num (range: -1:1)

fBodyAcc-std()-Z	| the average value for this feature, num (range: -1:1)

fBodyAccJerk-mean()-X	| the average value for this feature, num (range: -1:1)

fBodyAccJerk-mean()-Y	| the average value for this feature, num (range: -1:1)

fBodyAccJerk-mean()-Z	| the average value for this feature, num (range: -1:1)

fBodyAccJerk-std()-X	| the average value for this feature, num (range: -1:1)

fBodyAccJerk-std()-Y	| the average value for this feature, num (range: -1:1)

fBodyAccJerk-std()-Z	| the average value for this feature, num (range: -1:1)

fBodyGyro-mean()-X	| the average value for this feature, num (range: -1:1)

fBodyGyro-mean()-Y	| the average value for this feature, num (range: -1:1)

fBodyGyro-mean()-Z	| the average value for this feature, num (range: -1:1)

fBodyGyro-std()-X	| the average value for this feature, num (range: -1:1)

fBodyGyro-std()-Y	| the average value for this feature, num (range: -1:1)

fBodyGyro-std()-Z	| the average value for this feature, num (range: -1:1)

fBodyAccMag-mean()	| the average value for this feature, num (range: -1:1)

fBodyAccMag-std()	| the average value for this feature, num (range: -1:1)

fBodyBodyAccJerkMag-mean()	| the average value for this feature, num (range: -1:1)

fBodyBodyAccJerkMag-std()	| the average value for this feature, num (range: -1:1)

fBodyBodyGyroMag-mean()	| the average value for this feature, num (range: -1:1)

fBodyBodyGyroMag-std()	| the average value for this feature, num (range: -1:1)

fBodyBodyGyroJerkMag-mean()	| the average value for this feature, num (range: -1:1)

fBodyBodyGyroJerkMag-std()	| the average value for this feature, num (range: -1:1)


