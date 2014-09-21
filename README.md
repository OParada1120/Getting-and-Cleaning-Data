# Getting and Cleaning Data Assesment

## Description

The first thing I did in my solution is to check and see if the zip file was present in the current working directory and if it was not...then the file would be downloaded. I set up a warning message that would notify me if the file was already present.

Next, I needed to load all of the necessary files. The project states that I have to assumed that all of the files are in the structure that they were in the zip file with the main directory being the default working directory for my work. The the column names on each of the test and training set files were included and then I used cbind() to append the subject and activity IDs.

Finally, both files were merged using rbind().
