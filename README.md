Getting-CleaningData
====================
The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. 
The goal is to prepare tidy data that can be used for later analysis.
This repo contains:
1) a tidy data s
2) script for performing the analysis
3) a code book that describes the variables, the data, and any transformations  performed to clean up the 
data called CodeBook.md. 
4) README
This repo explains how all of the scripts work and how they are connected.  

#Getting and Cleaning Data Course Project
========================================
This file describes how run_analysis.R script works.
* First, unzip the data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip and rename the folder with "UCI HAR data".
* Make sure the folder "UCI HAR data" and the run_analysis.R script are both in the current working directory.
* Second, use source("run_analysis.R") command in RStudio. 
* Third, you will find result.txt as output file generated in the current working directory
* Finally, use data <- read.table("result.txt") command in RStudio to read the file. 