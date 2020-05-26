## Code Book

The code book summarizes the resulting data fields in tidy.txt

## About R Script
 File with R code "run_analysis.R" performs the following 5 steps 
 1. Reading the files and merging the training and test data sets to create one data set
  1.1 Reading files
  1.1.1 Reading training labels
  1.1.2 Reading testing labels
  1.1.3 Reading feature vector
  1.1.4 Reading activity labels
  1.2 Assigning variable names
  1.3 Merging all data in one set
  
  2. Extracting only the measurements on the mean and standard deviation for each measurement
  2.1 Reading variable names
  2.2 Create vector for defining ID, mean and standard deviation
  2.3 Making necessary subset from merged data set
  
  3. Using descriptive activity names to name the activities in the data set
  
  4. Appropriately labeling the data set with descriptive variable names
  
  5. Creating a second, indepedent tidy data set wtih the average of each variable for each activity and each subject
  5.1 Making second tidy data set
  5.2 Writing second tidy data set in txt file
  
  The code assumes all the data is present in the same folder, un-compressed and without names altered.
  
  ## About Variables:
      - x_train, y_train, x_test, y_test, subject_train and subject_test contain the data from the downloaded files.
      - x_data, y_data and subject_data merge the previous datasets to further analysis.
      - features contains the correct names for the x_data dataset, which are applied to the column names stored in.
      
