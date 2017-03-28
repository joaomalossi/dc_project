## Getting and Cleaning Data - Course Project

The run_analysis.R script does the following:

1. Download the dataset if it does not exists
2. Load the activity and feature info
3. Loads the training and test datasets, keeping only the columns that reflect a mean or standard deviation
4. Loads the activity and subject data for each dataset, and merges the columns with the dataset
5. Merges the datasets
6. Converts the activity and subject columns into factors
7. Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.
8. The end result is in the file tidy.txt.
