Codebook

Title: Getting and Cleaning data course project

Variable description in the Tidy Data:

subject   - Subject who performed the activity
activity  - One of the six activities performed - WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING
TimeBodyAccelerometerMean()-X -  Body Acceleration mean in x direction
TimeBodyAccelerometerMean()-Y -  Body Acceleration mean in y direction
TimeBodyAccelerometerMean()-Z - Body Acceleration mean  in z direction
TimeBodyAccelerometerSTD()-X – Body Acceleration standard deviation in X direction
TimeBodyAccelerometerSTD()-Y - Body Acceleration standard deviation in X direction
TimeBodyAccelerometerSTD()-Z Body Acceleration standard deviation in X direction
TimeGravityAccelerometerMean()-X – Gravity accelerometer mean in X direction
TimeGravityAccelerometerMean()-Y – Gravity accelerometer mean in Y direction
TimeGravityAccelerometerMean()-Z – Gravity accelertometer mean in Z direction
TimeGravityAccelerometerSTD()-X – Gravity accelertometer standard deviation in x direction
TimeGravityAccelerometerSTD()-Y – Gravity accelerometer standard deviation in y direction
TimeGravityAccelerometerSTD()-Z  - Gravity accelerometer standard deviation in z direction
TimeBodyAccelerometerJerkMean()-X – Body accelerometer jerk mean in x direction 
TimeBodyAccelerometerJerkMean()-Y – Body accelerometer jerk mean in y direction
TimeBodyAccelerometerJerkMean()-Z – Body accelerometer jerk mean in z direction
TimeBodyAccelerometerJerkSTD()-X – Body accelerometer jerk standard deviation in x direction
TimeBodyAccelerometerJerkSTD()-Y – Body accelerometer jerk standard deviation in y direction
TimeBodyAccelerometerJerkSTD()-Z – Body accelerometer jerk standard deviation in z direction
TimeBodyGyroscopeMean()-X – Body gyroscope mean in x direction
TimeBodyGyroscopeMean()-Y – Body gyroscope mean in y direction
TimeBodyGyroscopeMean()-Z – Body gyroscope mean in z direction
TimeBodyGyroscopeSTD()-X – Body gyroscope standard deviation in x direction
TimeBodyGyroscopeSTD()-Y – Body gyroscope standard deviation in y direction
TimeBodyGyroscopeSTD()-Z – Body gyroscope standard deviation in z direction
TimeBodyGyroscopeJerkMean()-X – Body gyroscope jerk mean in x direction
TimeBodyGyroscopeJerkMean()-Y – Body gyroscope jerk mean in y direction 
TimeBodyGyroscopeJerkMean()-Z – Body gyroscope jerk mean in z direction
TimeBodyGyroscopeJerkSTD()-X  - Body gyroscope jerk standard deviation in x direction
TimeBodyGyroscopeJerkSTD()-Y – Body gyroscope jerk standard deviation in y direction
TimeBodyGyroscopeJerkSTD()-Z – Body gyroscope jerk standard deviation in z direction
TimeBodyAccelerometerMagnitudeMean() – Body accelerometer magnitude mean
TimeBodyAccelerometerMagnitudeSTD() – Body accelerometer magnitude standard deviation
TimeGravityAccelerometerMagnitudeMean() – Gravity accelerometer magnitude mean
TimeGravityAccelerometerMagnitudeSTD() – Gravity Accelerometer magnitude standard deviation
TimeBodyAccelerometerJerkMagnitudeMean() – Body accelerometer jerk magnitude mean
TimeBodyAccelerometerJerkMagnitudeSTD() – Body accelerometer jerk magnitude standard deviation
TimeBodyGyroscopeMagnitudeMean() – Body gyroscope magnitude mean
TimeBodyGyroscopeMagnitudeSTD() – Body gryscope magnitude standard deviation
TimeBodyGyroscopeJerkMagnitudeMean() – Body gyroscope jerk magnitude mean
TimeBodyGyroscopeJerkMagnitudeSTD() – Body gyroscope jerk magnitude standard deviation
FrequencyBodyAccelerometerMean()-X – Frequency Body accelerometer mean in x direction
FrequencyBodyAccelerometerMean()-Y – Frequency Body accelerometer mean in y direction
FrequencyBodyAccelerometerMean()-Z - Frequency Body accelerometer mean in z direction
FrequencyBodyAccelerometerSTD()-X - Frequency Body accelerometer standard deviation in x direction
FrequencyBodyAccelerometerSTD()-Y - Frequency Body accelerometer standard deviation in y direction
FrequencyBodyAccelerometerSTD()-Z - Frequency Body accelerometer standard deviation in z direction
FrequencyBodyAccelerometerJerkMean()-X  - Frequency Body accelerometer jerk mean in x direction
FrequencyBodyAccelerometerJerkMean()-Y - Frequency Body accelerometer jerk mean in y direction
FrequencyBodyAccelerometerJerkMean()-Z - Frequency Body accelerometer jerk mean in z direction
FrequencyBodyAccelerometerJerkSTD()-X - Frequency Body accelerometer jerk standard deviation in x direction
FrequencyBodyAccelerometerJerkSTD()-Y - Frequency Body accelerometer jerk standard deviation in y direction
FrequencyBodyAccelerometerJerkSTD()-Z – Frequency Body accelerometer jerk standard deviation in z direction
FrequencyBodyGyroscopeMean()-X - Frequency Body gyroscope mean in x direction
FrequencyBodyGyroscopeMean()-Y - Frequency Body gyroscope mean in y  direction
FrequencyBodyGyroscopeMean()-Z - Frequency Body gyroscope mean in z direction
FrequencyBodyGyroscopeSTD()-X - Frequency Body gyroscope standard deviation in x direction
FrequencyBodyGyroscopeSTD()-Y – Frequency Body gyroscope standard deviation in y direction
FrequencyBodyGyroscopeSTD()-Z – Frequency Body gyroscope standard deviation in z direction
FrequencyBodyAccelerometerMagnitudeMean() - Frequency Body accelerometer magnitude mean
FrequencyBodyAccelerometerMagnitudeSTD() - Frequency Body accelerometer magnitude standard deviation
FrequencyBodyAccelerometerJerkMagnitudeMean() - Frequency Body accelerometer jerk magnitude mean
FrequencyBodyAccelerometerJerkMagnitudeSTD() - Frequency Body accelerometer jerk magnitude standard deviation
FrequencyBodyGyroscopeMagnitudeMean() - Frequency Body gyroscope jerk magnitude mean
FrequencyBodyGyroscopeMagnitudeSTD()  - Frequency Body gyroscope jerk magnitude standard deviation
FrequencyBodyGyroscopeJerkMagnitudeMean() - Frequency Body gyroscope jerk magnitude mean
FrequencyBodyGyroscopeJerkMagnitudeSTD() - Frequency Body gyroscope jerk magnitude standard deviation



Transformation performed on raw data:

- Merged subject , activity and feature test and train dataset.
- Extracted only mean and standard deviation measurement columns
- Applied descriptive activity names
- Appied appropriate descriptive variable names to the dataset
- Created final tidy dataset with the average of each variable and each subject
