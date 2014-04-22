
#run_analysis.R script Explanation

## Steps for Cleaning Data and Creating Tidy Data Set

###1. Creating Data Frames for Train and Test Data
Read in data for both train and test data and created a data frame for
each.
###2. Read in list of features
Read in list of features for use as column names for overall data frame
###3. Combined Test and Train into data frame
Combined Test and Train data frames into a singular data frame and
added labels based off feature list and general info
###4. Added comments to clarify code
Added comments to clarify code for combining data frames and adding
column names to overall data frame.
###5. Read in Activities into Data Frame
Read in activity_labels.txt into a data frame
###6. Merge Activity and OverallData dataframes
Merge Activity and OverallData data frames and remove Activity_ID since it is redundant.
###7. Extract only mean() and std() measurements
Extract only mean() and std() measurements from the OverallData data
frame
###8. Reorder data frame
Re-order columns of data frame so that Subject_ID is first
###9. Order rows based off Subject_ID
Order the rows in the OverallDataReordered based off Subject_ID
###10. Rename Feature Labels
Rename Feature Labels in Data frame to be more Descriptive
###11. Created tidy data by avg of each variable
Created data frame of tidy data based on avg of each variable based on
subject and activity
###12. Write Tidy Data to CSV file
Added code to write tidy data to a CSV file