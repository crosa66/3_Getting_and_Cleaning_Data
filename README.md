# 3_Getting_and_Cleaning_Data
Proyecto módulo 4

# Scripts 

1. File run_analysis.R is the one that contains the syntax to respond to the tasks requested in the job.

2. The file tity.txt presents the ordered data set

3. This is the link to the Github repository, https://github.com/crosa66/3_Getting_and_Cleaning_Data.git
   
5. A codebook that describes the variables, the data, and any transformations or work you've done to clean the data called CodeBook.md

# Getting and Cleaning Data Course Project

 The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis. You will be graded by your peers on a series of yes/no questions related to the project. You will be required to submit: 1) a tidy data set as described below, 2) a link to a Github repository with your script for performing the analysis, and 3) a code book that describes the variables, the data, and any transformations or work that you performed to clean up the data called CodeBook.md. You should also include a README.md in the repo with your scripts. This repo explains how all of the scripts work and how they are connected.

One of the most exciting areas in all of data science right now is wearable computing - see for example 
this article 
. Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most advanced algorithms to attract new users. The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Here are the data for the project:
 
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

You should create one R script called run_analysis.R that does the following. 

Merges the training and the test sets to create one data set.

Extracts only the measurements on the mean and standard deviation for each measurement. 

Uses descriptive activity names to name the activities in the data set

Appropriately labels the data set with descriptive variable names. 

From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

# run_analysis.R 

The file does the following:
1. Read in All Data
2. Read all the data and split it into the train and test set
3. Add Descriptive Headers to Data.
4. Find and remove unwanted variables. Only mean and Standard Deviation values.
5. Merge datasets train and test.
6. Write cleaned dataset 


