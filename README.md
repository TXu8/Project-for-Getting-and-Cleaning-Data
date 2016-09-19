# Project-for-Getting-and-Cleaning-Data
# Tianhao Xu

# My analysis file first creates a directory for the file, then downloads the file to that directory.
# Next, I unzip the file and readin the relevant data files
# I then stack the test and train versions of the Subject, X (features) and Y (activity) datasets together.
# Next, I assign names to these datasets, before combining the Subject, features and activity datasets. I use the names
# from features.txt to name the fields in the features dataset.
# I then subset a dataset with only the fields with mean() and std() in the field name, as well as the Subject and Activity fields.
# I can then merge on the Activity labels on the Activity field using the activity_labels.txt dataset.
# I then rename the field names so that they are more descriptive.
# Finally, I create a tidy dataset of the average of each variable for each activity and each subject
