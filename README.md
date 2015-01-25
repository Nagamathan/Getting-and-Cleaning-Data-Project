# Getting-and-Cleaning-Data-Project
Getting-and-Cleaning-Data-Project
Generate Dataset

Checkout the repo, and run the script run_analysis.R.

source("run_analysis.R")

This will download the required package (plyr) and the required data from (https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) and 

store it in a zip file called data.zip, After this a new folder will be generated (results/) containing the two datasets.

dataset1.csv - 10299 rows and 81 cols
dataset2.csv - 180 rows and 81 cols
Include dataset

The data is located in the results folder  dataset1 <- read.csv("results/dataset1.csv") dataset2 <- read.csv("results/dataset2.csv")
