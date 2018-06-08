# cleaning_and_getting_data
This is the  project done for the Coursera online course "Getting and Cleaning Data". The R code, "run_analysis.R", does the job as follows:

Downloads the dataset if it does not already exist in the working directory
Loads the activity and feature info
Loads both the training and test datasets, keeping only those columns reflecting mean or standard deviation
Loads the activity and subject data for each dataset, and merges those columns with the dataset
Merges the two datasets
Converts the activity and subject columns into factors
Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.
The end result is the file "tidy.txt".
