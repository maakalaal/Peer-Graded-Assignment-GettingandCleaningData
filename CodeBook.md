## Task Information 

I have divided my code into steps with each step referring to the question at hand. 

Step 1. Merges the training and the test sets to create one data set.

Step 2. Extracts only the measurements on the mean and standard deviation for each measurement. 

Step 3. Uses descriptive activity names to name the activities in the data set

Step 4. Appropriately labels the data set with descriptive variable names. 

Step 5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## Variable Information

Step 1 assigns variables trainX, trainY, trainsubject, testX, testY, testsubject from the data we have unzipped

train_data is the combined train data (column bind used to combine X, Y and subject information)
test_data is the combined train data (column bind used to combine X, Y and subject information)

merged_dataset is the tidy dataset which contains all the train and test information

Step 5 generates the second tidy dataset in the variable mean_var_customer_activity which is then exported as "secTidySet.txt" in the current directory
