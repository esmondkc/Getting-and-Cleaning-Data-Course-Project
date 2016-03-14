# Getting-and-Cleaning-Data-Course-Project
This is the course project for the Getting and Cleaning Data Coursera course. 
The R script, run_analysis.R, does the following:

1. Download the dataset in the working directory for further analysis
2. Load the activity info
3. Loads both the training and test data
4. Loads the activity and subject data for each set of data, and merges those columns with the data
5. Merges the two data
6. Converts the activity and subject columns into factors
7. Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.
8. The end result is shown in the file tidy.txt.
