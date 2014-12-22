Getting And Cleaning Data Project - Coursera 
===============

How to run the script
---------------------
To obtain a tidy dataset you have to run the script run_analysis.R from the root directory where the test and training dataset are placed.
Example of directory structure: 
- /root/run_analysis.R
- /root/test
- /root/train

All you have to do is source the script in R and run it.

What the script does
---------------------
The run_analysis.R script basically loads the train and test data, it merges them and finally it gives a more easy-to-understand appearance to data.
Below are listed the steps the script performs:
1.  Load and merge test-set data: load features variables, subjects and activities.
2.  Do the same for train-set data
3.  Merge train and test data
4.  Extract names of the measurements (features) and keep only features with name containing "mean" or "std".
5.  Extract activity names from file and assign those names to the corresponding activity id in dataset
6.  Extract features names from file and assign those names to every features colunm in dataset
6.  Compute the average value of all features for each subject and each activity
7.  Write the resulting dataset to file

Codebook
--------
For the codebook see codebook.txt



