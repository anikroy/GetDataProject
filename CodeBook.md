The dataset is based on data from [1], downloaded from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

Training and the test sets were merged to create one data set
_____________________________________________________________

* test\X_test.txt, test\y_test.txt, test\subject_test.txt were merged with 
* train\X_train.txt, train\y_train.txt, train\subject_train.txt 
This table can be found in the R code as "dat" 

From the "dat" table a smaller tidy data table was formed aggregating the averages for each mean and standard deviation variable for each subject for each activity.

Column names:
_____________

 [1] "activity" - Name of activity performed can be one of the following: WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING                
 [2] "subject"  - Range of values between 1-30 indicating the subject                    
 [3] "tbodyaccmeanx"               
 [4] "tbodyaccmeany"               
 [5] "tbodyaccmeanz"               
 [6] "tbodyaccstdx"                
 [7] "tbodyaccstdy"                
 [8] "tbodyaccstdz"                
 [9] "tgravityaccmeanx"            
[10] "tgravityaccmeany"            
[11] "tgravityaccmeanz"            
[12] "tgravityaccstdx"             
[13] "tgravityaccstdy"             
[14] "tgravityaccstdz"             
[15] "tbodyaccjerkmeanx"           
[16] "tbodyaccjerkmeany"           
[17] "tbodyaccjerkmeanz"           
[18] "tbodyaccjerkstdx"            
[19] "tbodyaccjerkstdy"            
[20] "tbodyaccjerkstdz"            
[21] "tbodygyromeanx"              
[22] "tbodygyromeany"              
[23] "tbodygyromeanz"              
[24] "tbodygyrostdx"               
[25] "tbodygyrostdy"               
[26] "tbodygyrostdz"               
[27] "tbodygyrojerkmeanx"          
[28] "tbodygyrojerkmeany"          
[29] "tbodygyrojerkmeanz"          
[30] "tbodygyrojerkstdx"           
[31] "tbodygyrojerkstdy"           
[32] "tbodygyrojerkstdz"           
[33] "tbodyaccmagmean"             
[34] "tbodyaccmagstd"              
[35] "tgravityaccmagmean"          
[36] "tgravityaccmagstd"           
[37] "tbodyaccjerkmagmean"         
[38] "tbodyaccjerkmagstd"          
[39] "tbodygyromagmean"            
[40] "tbodygyromagstd"             
[41] "tbodygyrojerkmagmean"        
[42] "tbodygyrojerkmagstd"         
[43] "fbodyaccmeanx"               
[44] "fbodyaccmeany"               
[45] "fbodyaccmeanz"               
[46] "fbodyaccstdx"                
[47] "fbodyaccstdy"                
[48] "fbodyaccstdz"                
[49] "fbodyaccmeanfreqx"           
[50] "fbodyaccmeanfreqy"           
[51] "fbodyaccmeanfreqz"           
[52] "fbodyaccjerkmeanx"           
[53] "fbodyaccjerkmeany"           
[54] "fbodyaccjerkmeanz"           
[55] "fbodyaccjerkstdx"            
[56] "fbodyaccjerkstdy"            
[57] "fbodyaccjerkstdz"            
[58] "fbodyaccjerkmeanfreqx"       
[59] "fbodyaccjerkmeanfreqy"       
[60] "fbodyaccjerkmeanfreqz"       
[61] "fbodygyromeanx"              
[62] "fbodygyromeany"              
[63] "fbodygyromeanz"              
[64] "fbodygyrostdx"               
[65] "fbodygyrostdy"               
[66] "fbodygyrostdz"               
[67] "fbodygyromeanfreqx"          
[68] "fbodygyromeanfreqy"          
[69] "fbodygyromeanfreqz"          
[70] "fbodyaccmagmean"             
[71] "fbodyaccmagstd"              
[72] "fbodyaccmagmeanfreq"         
[73] "fbodybodyaccjerkmagmean"     
[74] "fbodybodyaccjerkmagstd"      
[75] "fbodybodyaccjerkmagmeanfreq" 
[76] "fbodybodygyromagmean"        
[77] "fbodybodygyromagstd"         
[78] "fbodybodygyromagmeanfreq"    
[79] "fbodybodygyrojerkmagmean"    
[80] "fbodybodygyrojerkmagstd"     
[81] "fbodybodygyrojerkmagmeanfreq"

----------------------------------------------------------
Names of these variables were slightly altered from there original names in features.txt
The values are averages of each variable for each activity and each subject.

[1] Davide Anguita, Alessandro Ghio, Luca Oneto, Xavier Parra and Jorge L. Reyes-Ortiz. Human Activity Recognition on Smartphones using a Multiclass H