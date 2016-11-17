#Getting and Cleaning data project code book.

The code uses the following formulas : 

1. FileURL to load data from the internet.
2. A subdirectory is created where the zip file is extracted to by using the unzip command.
3. The read.table command is used to 7 extracted files.
4. The Rbind command is created to combine the two X files as they have the same columns.  
5. The same is also applicable to the combining of the two Y files and the two subject files.
6. After modifying the column names, the files are combined with the cbind (column bind) formula. 
7. The plyr package is used to create the subset of the data and finally the write.table is used to write the file. 

The files and the variables are as follows :
- 'features.txt': List of all features.
- 'activity_labels.txt': Links the class labels with their activity name.
- 'train/X_train.txt': Training set.
- 'train/y_train.txt': Training labels.
- 'test/X_test.txt': Test set.
- 'test/y_test.txt': Test labels.

There are 561 variables in the file. The first 20 are listed below : 
1 tBodyAcc-mean()-X
2 tBodyAcc-mean()-Y
3 tBodyAcc-mean()-Z
4 tBodyAcc-std()-X
5 tBodyAcc-std()-Y
6 tBodyAcc-std()-Z
7 tBodyAcc-mad()-X
8 tBodyAcc-mad()-Y
9 tBodyAcc-mad()-Z
10 tBodyAcc-max()-X
11 tBodyAcc-max()-Y
12 tBodyAcc-max()-Z
13 tBodyAcc-min()-X
14 tBodyAcc-min()-Y
15 tBodyAcc-min()-Z
16 tBodyAcc-sma()
17 tBodyAcc-energy()-X
18 tBodyAcc-energy()-Y
19 tBodyAcc-energy()-Z
20 tBodyAcc-iqr()-X

