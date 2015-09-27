# GettingData
Repository as part of Coursera John Hopkins Specialization Course
Created by Jordan DeHerrera on 9/27/2015

# File List
## Data - download and extract from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 
* Test (folder) - contains test data
* Train (folder - contains training data
* activity_labels.txt - part of data set; used to label activities in data set
* features.txt - part of data set; used for header for combined file

## Script and Output
* run_analysis.R - script that prepares tidy data text file as well as all of required tasks
* TidyData.txt - output of R script - uploaded as required by project

# How to Use
1.  Download the data and R script into the same working directory
2.  Run the R script
3.  Use the following to save the output to a text file:

```{r}
write.table(dataset_mean_std_avg, "TidyData.txt", row.names = FALSE)
```
