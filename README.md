# Getting-and-Cleaning-Data-Course-Project
This repository contains the required scripts and file for course project Getting and Cleaning Data Coursera course. 
IT contains a R script file run_analysis.R which does the following task:

It downloads dataset if there is not such daaset found in working directory or folder
Loads activity and feature info
Then loads both training and test datasets but keeping only the columns which reflect a mean or standard deviation
Then it loads activity and subject data for each dataset, and after that it merges those columns with dataset
Merging of two datasets
Conversion of activity and subject columns into factors
It creates a tidy dataset that has average (mean) value of each variable for each subject and activity pairs.
Created a final end result in file tidy.txt.
