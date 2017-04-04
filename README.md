# Anomaly Detection - Updated

This is an updated version of the Anomaly detection algorithm provided by AQIBSAEED in his GitHub profile. I have slightly changed the program to suit my own needs and have shared the code in the hope that someone else will find it useful.

I have made three changes to make the program more general. They are:
1. Most data scientists will have only a single traiing file rather than 3 different training files. Hence I have modified the program to spolit a single training file into 3 different files as required by the algorithm: tr_data, cv_data and gt_data
'2. Once I split the files, I modify the input so that only Numeric variables are fed into the Anamoly Detection algorithm. This makes the process of detecting anamolies easier.
3. The algo also accepts any number of variables as input. Hence the plotting function is not included since the previous version assumed plotting using 2 variables only. 

Once the above steps are done, the rest is easy. You just have to run the Anamoly Detection algorithm as defined by AQIBSAEED.

The algorithm remains the same anomaly detection algorithm based on estimation of gaussian distribution. This is a Python implementation of algorithm discussed by Andrew Ng in his course of Machine Learning on Coursera.  
