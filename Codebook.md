## Libraries Used
#### The libraries used in this assignment are "data.table" and "dplyr". data.table could handling large data as tables. dplyr could aggregate variables to create the tidy data.

## Read Supporting Metadata
#### The supporting metadata are the name of the features and activities. They are loaded into variables featureNames and activityLabels.

## Format training and test data sets
#### Read training data
#### Read test data

# Merge the training and the test sets to create one data set
#### We can use combine the respective data and stare the results in training and test data sets corresponding to subject, activity and features.
#### Naming the columns
#### Merge the data

# Extracts only the measurements on the mean and standard deviation for each measurement

# Uses descriptive activity names to name the activities in the data set

# Appropriately labels the data set with descriptive variable names
#### Acc can be replaced with Accelerometer
#### Gyro can be replaced with Gyroscope
#### BodyBody can be replaced with Body
#### Mag can be replaced with Magnitude
#### Character f can be replaced with Frequency
#### Character t can be replaced with Time

# From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject
