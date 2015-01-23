Getting and Cleaning Data - Course Project
==========================================

This repository contains the R code and documentation files for the John Hopkins University course "Getting and Cleaning data", via Coursera.

The dataset being used is: [Human Activity Recognition Using Smartphones](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)

## Files

The raw files from Samsung can be downloaded here as of 01/22/2015 https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

CodeBook.md describes the variables, and the data.

run_analysis.R contains all the code to perform the analyses on the raw data that results in tidy data.

The purpose of run_analysis.R is to stitch together the different parts the data from different files. 

List of things that were done:
1. Filtered for only the mean and standard deviation of variables. 
2. Merged the testing and training data sets.
3. Formatted the column names for consistency, and readability
4. Included the actual named of activities instead of integers.
5. Turned the subject and activity variables into factor variables.  

The output is called tidy.txt.