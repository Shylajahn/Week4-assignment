Codebook for Coursera Course
========================
[Getting and Cleaning Data](https://class.coursera.org/getdata-008)
File: [tidyData.txt](https://github.com/dholtz/GettingAndCleaningData/blob/master/tidyData.txt)
 Variable Name | Variable Type  | Values | Description
 ------------- | -------------  | ------------- | ------------- 
 subject       | numerical      | 1:30  	     | Subject id numbers
 activityName  | factor with 6 levels        | WALKING, WALKING\_UPSTAIRS, WALKING\_DOWNSTAIRS, SITTING, STANDING, LAYING | Links the class labels with their activity name. (from: https://github.com/dholtz/GettingAndCleaningData/blob/master/project_data/activity_labels.txt)
**Features/Measures** | numeric | Features/Measures are normalized and bounded within [-1,1]. | Mean or standard deviation of the triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration
**Features/Measures** | **numeric** | **Features/Measures are normalized and bounded within [-1,1].** | **Mean or standard deviation of the triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration**
tBodyAcc-mean()-X |
tBodyAcc-mean()-Y |
tBodyAcc-mean()-Z |
@@ -75,4 +75,4 @@ fBodyBodyAccJerkMag-std() |
fBodyBodyGyroMag-mean() |
fBodyBodyGyroMag-std() |
fBodyBodyGyroJerkMag-mean() |
fBodyBodyGyroJerkMag-std() |
fBodyBodyGyroJerkMag-std() |x 
