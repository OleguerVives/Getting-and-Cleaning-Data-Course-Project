# Codebook

## List of variables used in the script
* **fileUrl:** URL where the zipped data sets provided for the project are stored

* **features:** variable storing *features.txt* provided data set
* **activityLabels:** variable storing *activity_labels.txt* provided data set

* **subject_test, X_test and y_test:** data sets storing test data provided
* **mergedTest:** data set where all the test data has been merged
* **subject_training, X_training and y_training:** data sets storing training data provided
* **mergedTraining:** data set where all the training data has been merged
* **mergedData:** data set where all the provided data *(test and training)* has been merged

* **mean_std:** vector containing the position of the mean() and std() measurement

* **tifyData:** data set containing the subject, activity and mean() and std() measurements
* **finalDataSet:** tidy data set, created from *tidyData*, with the average of each variable for each activity and each subject
