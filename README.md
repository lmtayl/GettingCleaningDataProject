Getting and Cleaning Data Project
=================================

### run_analysis.R

After downloading the UCI HAR Dataset, set this folder as your working directory. Then run the code in run_analysis.R. This code combines the test and train datasets, keeps only variables including "mean" or "std" in the original variable name, and creates a tidy data set containing the mean of 86 measurements for 30 participants in each of 6 activities. This tidy data set, with dimensions 180X88, is output to a text file, project_data.txt.

### CodeBook.md

Descriptions for each of the 88 variables in the tidy data set, project_data.txt, are included in CodeBook.md.