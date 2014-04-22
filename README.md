
#run_analysis.R script Explanation

## Steps for Cleaning Data and Creating Tidy Data Set

1. Creating Data Frames for Train and Test Data
  1. Read in data for both train and test data and created a data frame for
each.
1. Read in list of features
  1. Read in list of features for use as column names for overall data frame
1. Combined Test and Train into data frame
  1. Combined Test and Train data frames into a singular data frame and
added labels based off feature list and general info
1. Added comments to clarify code
  1. Added comments to clarify code for combining data frames and adding
column names to overall data frame.
1. Read in Activities into Data Frame
  1. Read in activity_labels.txt into a data frame
1. Merge Activity and OverallData dataframes
  1. Merge Activity and OverallData data frames and remove Activity_ID since it is redundant.
1. Extract only mean() and std() measurements
  1. Extract only mean() and std() measurements from the OverallData data
frame
1. Reorder data frame
  1. Re-order columns of data frame so that Subject_ID is first
1. Order rows based off Subject_ID
  1. Order the rows in the OverallDataReordered based off Subject_ID
1. Rename Feature Labels
  1. Rename Feature Labels in Data frame to be more Descriptive
1. Created tidy data by avg of each variable
  1. Created data frame of tidy data based on avg of each variable based on
subject and activity
1. Write Tidy Data to CSV file
  1. Added code to write tidy data to a CSV file