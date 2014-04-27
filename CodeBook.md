#CodeBook for Getting and Cleaning Data Peer Assignment

###Variables
This section describes the variables in my final dataset.

Column Names

1. **Subject_ID** is the collection of subject IDs from `train` and `test` data.                                                                
1. **Activity** is the collection of Activity IDs converted to their appropriate Activity labels from `train` and `test` data.                                                                  
1. **Time_Domain_Body_Accelerometer_Mean_X** renamed from `tBodyAcc-mean()-X` in `features.txt` this variables data is collection of `train` and `test` data.                                    
1. **Time_Domain_Body_Accelerometer_Mean_Y** renamed from `tBodyAcc-mean()-Y` in `features.txt` this variables data is collection of `train` and `test` data.             
1. **Time_Domain_Body_Accelerometer_Mean_Z** renamed from `tBodyAcc-mean()-Z` in `features.txt` this variables data is collection of `train` and `test` data.               
1. **Time_Domain_Body_Accelerometer_Standard_Deviation_X** renamed from `tBodyAcc-std()-X` in `features.txt` this variables data is collection of `train` and `test` data.            
1. **Time_Domain_Body_Accelerometer_Standard_Deviation_Y** renamed from `tBodyAcc-std()-Y` in `features.txt` this variables data is collection of `train` and `test` data.             
1. **Time_Domain_Body_Accelerometer_Standard_Deviation_Z** renamed from `tBodyAcc-std()-Z` in `features.txt` this variables data is collection of `train` and `test` data.                         
1. **Time_Domain_Gravity_Accelerometer_Mean_X** renamed from `tGravityAcc-mean()-X` in `features.txt` this variables data is collection of `train` and `test` data.                                   
1. **Time_Domain_Gravity_Accelerometer_Mean_Y** renamed from `tGravityAcc-mean()-Y` in `features.txt` this variables data is collection of `train` and `test` data.                                    
1. **Time_Domain_Gravity_Accelerometer_Mean_Z** renamed from `tGravityAcc-mean()-Z` in `features.txt` this variables data is collection of `train` and `test` data.                                    
1. **Time_Domain_Gravity_Accelerometer_Standard_Deviation_X** renamed from `tGravityAcc-std()-X` in `features.txt` this variables data is collection of `train` and `test` data.                      
1. **Time_Domain_Gravity_Accelerometer_Standard_Deviation_Y** renamed from `tGravityAcc-std()-Y` in `features.txt` this variables data is collection of `train` and `test` data.                      
1. **Time_Domain_Gravity_Accelerometer_Standard_Deviation_Z** renamed from `tGravityAcc-std()-Z` in `features.txt` this variables data is collection of `train` and `test` data.                      
1. **Time_Domain_Body_Accelerometer_Jerk_Mean_X** renamed from `tBodyAccJerk-mean()-X` in `features.txt` this variables data is collection of `train` and `test` data.                                  
1. **Time_Domain_Body_Accelerometer_Jerk_Mean_Y** renamed from `tBodyAccJerk-mean()-Y` in `features.txt` this variables data is collection of `train` and `test` data.                                  
1. **Time_Domain_Body_Accelerometer_Jerk_Mean_Z** renamed from `tBodyAccJerk-mean()-Z` in `features.txt` this variables data is collection of `train` and `test` data.                                  
1. **Time_Domain_Body_Accelerometer_Jerk_Standard_Deviation_X** renamed from `tBodyAccJerk-std()-X` in `features.txt` this variables data is collection of `train` and `test` data.                    
1. **Time_Domain_Body_Accelerometer_Jerk_Standard_Deviation_Y** renamed from `tBodyAccJerk-std()-Y` in `features.txt` this variables data is collection of `train` and `test` data.                    
1. **Time_Domain_Body_Accelerometer_Jerk_Standard_Deviation_Z** renamed from `tBodyAccJerk-std()-Z` in `features.txt` this variables data is collection of `train` and `test` data.                    
1. **Time_Domain_Body_Gyroscope_Mean_X** renamed from `tBodyGyro-mean()-X` in `features.txt` this variables data is collection of `train` and `test` data.                                           
1. **Time_Domain_Body_Gyroscope_Mean_Y** renamed from `tBodyGyro-mean()-Y` in `features.txt` this variables data is collection of `train` and `test` data.                                           
1. **Time_Domain_Body_Gyroscope_Mean_Z** renamed from `tBodyGyro-mean()-Z` in `features.txt` this variables data is collection of `train` and `test` data.                                           
1. **Time_Domain_Body_Gyroscope_Standard_Deviation_X** renamed from `tBodyGyro-std()_X` in `features.txt` this variables data is collection of `train` and `test` data.                             
1. **Time_Domain_Body_Gyroscope_Standard_Deviation_Y** renamed from `tBodyGyro-std()-Y` in `features.txt` this variables data is collection of `train` and `test` data.                             
1. **Time_Domain_Body_Gyroscope_Standard_Deviation_Z** renamed from `tBodyGyro-`std()-Z` in `features.txt` this variables data is collection of `train` and `test` data.                             
1. **Time_Domain_Body_Gyroscope_Jerk_Mean_X** renamed from `tBodyGyroJerk-mean()-X` in `features.txt` this variables data is collection of `train` and `test` data.                                      
1. **Time_Domain_Body_Gyroscope_Jerk_Mean_Y** renamed from `tBodyGyroJerk-mean()-Y` in `features.txt` this variables data is collection of `train` and `test` data.                                      
1. **Time_Domain_Body_Gyroscope_Jerk_Mean_Z** renamed from `tBodyGyroJerk-mean()-Z` in `features.txt` this variables data is collection of `train` and `test` data.                                      
1. **Time_Domain_Body_Gyroscope_Jerk_Standard_Deviation_X** renamed from `tBodyGyroJerk-std()-X` in `features.txt` this variables data is collection of `train` and `test` data.                        
1. **Time_Domain_Body_Gyroscope_Jerk_Standard_Deviation_Y** renamed from `tBodyGyroJerk-std()-Y` in `features.txt` this variables data is collection of `train` and `test` data.                        
1. **Time_Domain_Body_Gyroscope_Jerk_Standard_Deviation_Z** renamed from `tBodyGyroJerk-std()-Z` in `features.txt` this variables data is collection of `train` and `test` data.                        
1. **Time_Domain_Body_Accelerometer_Magnitude_Mean** renamed from `tBodyAccMag-mean()` in `features.txt` this variables data is collection of `train` and `test` data.                               
1. **Time_Domain_Body_Accelerometer_Magnitude_Standard_Deviation** renamed from `tBodyAccMag-std()` in `features.txt` this variables data is collection of `train` and `test` data.                 
1. **Time_Domain_Gravity_Accelerometer_Magnitude_Mean** renamed from `tGravityAccMag-mean()` in `features.txt` this variables data is collection of `train` and `test` data.                            
1. **Time_Domain_Gravity_Accelerometer_Magnitude_Standard_Deviation** renamed from `tGravityAccMag-std()` in `features.txt` this variables data is collection of `train` and `test` data.              
1. **Time_Domain_Body_Accelerometer_Jerk_Magnitude_Mean** renamed from `tBodyAccJerkMag-mean()` in `features.txt` this variables data is collection of `train` and `test` data.                          
1. **Time_Domain_Body_Accelerometer_Jerk_Magnitude_Standard_Deviation** renamed from `tBodyAccJerkMag-std()` in `features.txt` this variables data is collection of `train` and `test` data.            
1. **Time_Domain_Body_Gyroscope_Magnitude_Mean** renamed from `tBodyGyroMag-mean()` in `features.txt` this variables data is collection of `train` and `test` data.                                   
1. **Time_Domain_Body_Gyroscope_Magnitude_Standard_Deviation** renamed from `tBodyGyroMag-std()` in `features.txt` this variables data is collection of `train` and `test` data.                     
1. **Time_Domain_Body_Gyroscope_Jerk_Magnitude_Mean** renamed from `tBodyGyroJerkMag_mean()` in `features.txt` this variables data is collection of `train` and `test` data.                              
1. **Time_Domain_Body_Gyroscope_Jerk_Magnitude_Standard_Deviation** renamed from `tBodyGyroJerkMag-std()` in `features.txt` this variables data is collection of `train` and `test` data.                
1. **Frequency_Domain_Body_Accelerometer_Mean_X** renamed from `fBodyAcc-mean()-X` in `features.txt` this variables data is collection of `train` and `test` data.                                  
1. **Frequency_Domain_Body_Accelerometer_Mean_Y** renamed from `fBodyAcc-mean()-Y` in `features.txt` this variables data is collection of `train` and `test` data.                                  
1. **Frequency_Domain_Body_Accelerometer_Mean_Z** renamed from `fBodyAcc-mean()-Z` in `features.txt` this variables data is collection of `train` and `test` data.                                  
1. **Frequency_Domain_Body_Accelerometer_Standard_Deviation_X** renamed from `fBodyAcc-std()-X` in `features.txt` this variables data is collection of `train` and `test` data.                    
1. **Frequency_Domain_Body_Accelerometer_Standard_Deviation_Y** renamed from `fBodyAcc-std()-Y` in `features.txt` this variables data is collection of `train` and `test` data.                    
1. **Frequency_Domain_Body_Accelerometer_Standard_Deviation_Z** renamed from `fBodyAcc-std()-Z` in `features.txt` this variables data is collection of `train` and `test` data.                    
1. **Frequency_Domain_Body_Accelerometer_Jerk_Mean_X** renamed from `fBodyAccJerk-mean()-X` in `features.txt` this variables data is collection of `train` and `test` data.                             
1. **Frequency_Domain_Body_Accelerometer_Jerk_Mean_Y** renamed from `fBodyAccJerk-mean()-Y` in `features.txt` this variables data is collection of `train` and `test` data.                             
1. **Frequency_Domain_Body_Accelerometer_Jerk_Mean_Z** renamed from `fBodyAccJerk-mean()-Z` in `features.txt` this variables data is collection of `train` and `test` data.                             
11. **. Frequency_Domain_Body_Accelerometer_Jerk_Standard_Deviation_X** renamed from `fBodyAccJerk-std()-X` in `features.txt` this variables data is collection of `train` and `test` data.               
1. **Frequency_Domain_Body_Accelerometer_Jerk_Standard_Deviation_Y** renamed from `fBodyAccJerk-std()-Y` in `features.txt` this variables data is collection of `train` and `test` data.               
1. **Frequency_Domain_Body_Accelerometer_Jerk_Standard_Deviation_Z** renamed from `fBodyAccJerk-std()-Z` in `features.txt` this variables data is collection of `train` and `test` data.               
1. **Frequency_Domain_Body_Gyroscope_Mean_X** renamed from `fBodyGyro-mean()-X` in `features.txt` this variables data is collection of `train` and `test` data.                                     
1. **Frequency_Domain_Body_Gyroscope_Mean_Y** renamed from `fBodyGyro-mean()-Y` in `features.txt` this variables data is collection of `train` and `test` data.                                     
1. **Frequency_Domain_Body_Gyroscope_Mean_Z** renamed from `fBodyGyro-mean()-Z` in `features.txt` this variables data is collection of `train` and `test` data.                                      
1. **Frequency_Domain_Body_Gyroscope_Standard_Deviation_X** renamed from `fBodyGyro-std()-X` in `features.txt` this variables data is collection of `train` and `test` data.                        
1. **Frequency_Domain_Body_Gyroscope_Standard_Deviation_Y** renamed from `fBodyGyro-std()-Y` in `features.txt` this variables data is collection of `train` and `test` data.                        
1. **Frequency_Domain_Body_Gyroscope_Standard_Deviation_Z** renamed from `fBodyGyro-std()-Z` in `features.txt` this variables data is collection of `train` and `test` data.                        
1. **Frequency_Domain_Body_Accelerometer_Magnitude_Mean** renamed from `fBodyAccMag-mean()` in `features.txt` this variables data is collection of `train` and `test` data.                          
1. **Frequency_Domain_Body_Accelerometer_Magnitude_Standard_Deviation** renamed from `fBodyAccMag-std()` in `features.txt` this variables data is collection of `train` and `test` data.            
1. **Frequency_Domain_Body_Body_Accelerometer_Jerk_Magnitude_Mean** renamed from `fBodyBodyAccJerkMag-mean()` in `features.txt` this variables data is collection of `train` and `test` data.                
1. **Frequency_Domain_Body_Body_Accelerometer_Jerk_Magnitude_Standard_Deviation** renamed from `fBodyBodyAccJerkMag_std()` in `features.txt` this variables data is collection of `train` and `test` data.  
1. **Frequency_Domain_Body_Body_Gyroscope_Magnitude_Mean** renamed from `fBodyBodyGyroMag-mean()` in `features.txt` this variables data is collection of `train` and `test` data.                         
1. **Frequency_Domain_Body_Body_Gyroscope_Magnitude_Standard_Deviation** renamed from `fBodyBodyGyroMag-std()` in `features.txt` this variables data is collection of `train` and `test` data.           
1. **Frequency_Domain_Body_Body_Gyroscope_Jerk_Magnitude_Mean** renamed from `fBodyBodyGyroJerkMag-mean()` in `features.txt` this variables data is collection of `train` and `test` data.                    
1. **Frequency_Domain_Body_Body_Gyroscope_Jerk_Magnitude_Standard_Deviation** renamed from `fBodyBodyGyroJerkMag-std()` in `features.txt` this variables data is collection of `train` and `test` data.   
*Variables 3-68 above contain the average of their measurements grouped by subject and activity.

Variables in code:

1. **featuresTable**: data frame built off of `features.txt`
1. **features**: character vector of feature names.
1. **x_test**: data frame of `X_test.txt` data
1. **y_test**: data frame of `y_test.txt` data
1. **subject_test**: data frame of `subject_test.txt` data
1. **TestDF**: data frame built from a column bind of `subject_test`, `y_test`, and `x_test`
1. **x_train**: data frame of `X_train.txt` data
1. **y_train**: data frame of `y_train.txt` data
1. **subject_train**: data frame of `subject_train.txt` data
1. **TrainDF**: data frame built from a column bind of `subject_train`, `y_train`, and `x_train`
1. **OverallData**: data frame built from a row bind of `TestDF` and `TrainDF`
1. **new_Overall_Data**: data frame built from `OverallData` containing only columns with mean() and std() data
1. **activities**: data frame of `activity_labels.txt` data
1. **OverallDataActivities**: merge of `activities` and `new_Overall_Data` with Activity_ID column removed
1. **OverallDataReordered**: `OverallDataActivities` with Subject_ID as the first column
1. **SubjectOrderData**: `OverallDataReordered` ordered by Subject_ID
1. **AvgMeasurements**: data frame created from applying the mean over all measurements for each subject and activity


###Data
This section describes the data used to create my tidy data set.

These files are just from the extracted zip file in the present working directory.

1. Column Names
  * UCI HAR Dataset/features.txt
1. Test Data
  * UCI HAR Dataset/test/X_test.txt
  * UCI HAR Dataset/test/y_test.txt
  * UCI HAR Dataset/test/subject_test.txt
1. Train Data
  * UCI HAR Dataset/train/X_train.txt
  * UCI HAR Dataset/train/y_train.txt
  * UCI HAR Dataset/train/subject_train.txt
1. Activity Labels for Activity IDs in created data frame
  * UCI HAR Dataset/activity_labels.txt

Created tidy data is a collection of the above data.

###Transformations
1. Column bind data from `X_test`, `y_test`, and `subject_test` data to create data frame `TestDF`.
1. Column bind data from `X_train`, `y_train`, and `subject_train` data to create data frame `TrainDF`.
1. Row bind data from `TestDF` and `TrainDF` to create data frame `OverallData`.
1. Change the column names of `OverallData` to be Subject_ID, Activity_ID, and feature names from `feature.txt`.
1. Create a new data frame `new_OverallData` that pulls only the Subject_ID, Activity_ID, and only mean() and std() measurements.
1. Create a data frame `activities` from the `activity_labels.txt` with column names Activity_ID and Activity.
1. Create a data frame `OverallDataActivities` merge data frames `activities` and `new_OverallData` by Activity_ID and remove the Activity_ID column after the merge.
1. Create a data frame `OverallDataReordered` from reordering the columns in `OverallDataActivities` so that Subject_ID first.
1. Create a data frame `SubjectOrderData` that reorders the rows of `OverallDataReordered` based off of Subject_ID.
1. Rename the column names for `SubjectOrderData` so that the measurement labels are more clear.
1. Create a data frame `AvgMeasurements` by applying the mean on all measurements in `SubjectOrderData` by Subject_ID and Activity.
1. Create a CSV file TidyData.csv from the data frame `AvgMeasurements`.