The code book describes the variables, the data, and any transformations or work performed to clean up the data from Human Activity Recognition Using Smartphones
Data Set.
Data

Data

The tidydata.txt data file is a text file, containing space-separated values.
The first row contains the names of the variables, which are listed and described in the Variables section, and the following rows contain the values of these 
variables.

Variables
Each row contains, for a given subject and activity, 79 averaged signal measurements.

Identifiers
subjectID
Subject identifier, integer, ranges from 1 to 30.

actions
Activity identifier, string with 6 possible values:
WALKING: subject was walking WALKING_UPSTAIRS: subject was walking upstairs WALKING_DOWNSTAIRS: subject was walking downstairs SITTING: subject was sitting 
STANDING: subject was standing LAYING: subject was laying Average of measurements

the following cahnges to original data sets were performed
Merged the training and the test sets to create one data set.
Extracted only the measurements on the mean and standard deviation for each measurement. 
descriptive activity names were usedto name the activities in the data set
Appropriately labeled the data set with descriptive variable names. 
independent tidy data was created set with the average of each variable for each activity and each subject.
