Unzip the source ( https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip )

into a folder on your local drive, typically /Users/xxxxx/Downloads/ (replace xxxxx with proper name)

Put run_analysis.R to /Users/xxxxx/Downloads/UCI HAR Dataset/

in RStudio: setwd("/Users/xxxx/Downloads/UCI HAR Dataset")

and then: source("run_analysis.R")

The above will run the R script, reading the dataset and writing these files:

merged_clean_data.txt -- culminating in a merged data frame

data_set_with_the_averages.txt -- culminating into a tidy dataset.

The script normally runs for ~2 minutes, but "your mileage may vary", depending on your setup.

Use data <- read.table("data_set_with_the_averages.txt") to read the file.
