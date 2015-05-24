## Class Project for "Getting and Cleaning Data"

The class project for [Getting and Cleaning Data](https://www.coursera.org/course/getdata) 
involves reading in {"Human Activity Recognition Using Smartphones" data set] located at 
(http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones), 
and then perform data analysis on various data files merged into one data set, then
writtn output into a tidy data set.

** Steps execute activity **

1. Download the zip and unzip file contents [this URL](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip ).
2. Find and copy files below into your R working directory:
	* `features.txt`
	* `subject_train.txt`
	* `subject_test.txt`
	* `X_train.txt`
	* `X_test.txt`
	* `y_train.txt`
	* `y_test.txt`

3. run_analysis.R script requires [reshape2 package], at the R console, run install.packages("reshape2") command 
4. Load and execute run_analysis.R script, source("run_analysis.R")
5. Verify tidy data set file [tidy.csv](tidy.csv). exists ** 

Reference {code book](CodeBook.md). for data set column details
