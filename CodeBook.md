#Getting and Cleaning data project code book.

The code uses the following formulas : 

1. FileURL to load data from the internet.
2. A subdirectory is created where the zip file is extracted to by using the unzip command.
3. The read.table command is used to 7 extracted files.
4. The Rbind command is created to combine the two X files as they have the same columns.  
5. The same is also applicable to the combining of the two Y files and the two subject files.
6. After modifying the column names, the files are combined with the cbind (column bind) formula. 
7. The plyr package is used to create the subset of the data and finally the write.table is used to write the file. 
