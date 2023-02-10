# Project Title
Spam eMail Detection using Naive Bayes Classification Algorithm

# Description
For this project I took the Naive Bayes code that Dr. Brahma had provided us with and went ahead and completed it.

To beign with- we went ahead and created dictionaries including all the words, from which we then removed all non-alpha numeric values as well as items with length = 1. After which we created another dictionary extracting a list of 3000 of the most common words. Following that we went ahead to create a matrix with all 0 values. From that, we split the words based on the symbols that came in the middle and then continued on to count it.

After completing the setting up portion of the project, we moved on to splitting the dataset into train and test datasets. We then used the features matrix created ealier to fit the train and test datasets into. Using Gaussian Naive Bayes function, we trained the data so it can distinguish between spam and non-spam emails. After completing the training, we tested out the data for accuracy.

# Content
Import Packages
Data Cleaning and Preparation
Extract Features of the Dataset
Mount to Google Drive and set File Path
Use Train file to Train data and then Test for Accuracy

# How to Use the Project
This was a very interesting project that I have completed. In reality our inbox gets flooded with spam emails and it's interesting to see how the spftware distinguishes emails into spam and non-spam categories. Of course there is bound to be some error because no program is 100% accurate but it suggests a very good baseline to go off of.
