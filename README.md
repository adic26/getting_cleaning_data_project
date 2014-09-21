getting_cleaning_data_project
=============================

Project for getting and cleaning data

Author: Aditya Chugh

Importing all data into R in the following variables:

1.  activities
2.  features
3.  subject train
4.  subject test
5.  x_train
6.  y_train
7.  x_test
8.  y_test

Making a new dataset that would merge the following into a new variable

1.  Subject_data -- merges subject_train and subject_test
2.  x_data -- merges x_train and x_test
3.  y_data -- merges y_train and y_test


Clean up x_data by finding mean and standard deviation from feature coloumns:

1.  mean_std_columns -- grep data for mean|std
2.  x_data -- clean up data would contain mean and standard deviation correlated data
3.  copy over column names from features


Clean up Y data by substituting index with a meaningful name :

1 -- walking
2 -- walking_upstairs
3 -- walking_downstairs
4 -- sitting
5 -- standing
6 -- laying

Final sorting and merging

column bind the following data into a new frame called clean_data

1. subject_dat
2. y_data
3. x_data

all merged and combined into clean_data variable

Final creating a tidy set with average of each variable for each activity and each subject

Using Library plyr
"subset" is the final variable --> subsets all data from 'clean_data' by grouping subject and activity while taking a mean of other columns








