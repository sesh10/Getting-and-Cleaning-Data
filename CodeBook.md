1. First we check whether, the dataset is already present. If its not then we download it using download.file() command
2. library(): To load packages
3. features: Various labels/columns in dataset
4. activities: Describes various possible activities/actions
5. subject_test: The test set values for the column subject
6. x_test, y_test: The input and output test values respectively
7. subject_train: The train set values for the column subject
8. x_train, y_train: The input and output training dataset values
9. X: Combined input values
10. Y: Combined output values
11. Subject: Combined subject column values
12. Merged_Data: Combined input dataset
13. TidyData: Extracts only the measurements on the mean and standard deviation for each measurement.
14. FinalData: Independent tidy data set with the average of each variable for each activity and each subject.
