# Anomaly Detection

Anomaly detection is the problem of identifying data points that don't conform to expected (normal) behaviour. Unexpected data points are also known as outliers and exceptions etc. Anomaly detection has crucial significance in the wide variety of domains as it provides critical and actionable information. For example, an anomaly in MRI image scan could be an indication of the malignant tumor or anomalous reading from production plant sensor may indicate faulty component.

This repository provide an anomaly detection algortihm based on estimation of gaussian distribution. This is a Python implementation of algorithm discussed by Andrew Ng in his course of Machine Learning on Coursera.  

####################################################################################################
####### The original method is a neat method which seems to work fine for small data sets ##########
#######   but fails for large or real world data sets where there are lotsa variables. Hence  ######
#######   I have modified it.  So what I do is to select only the Numeric features in the data set
#######   and feed the Features to this. However you have to make sure you "normalize" the features.
####################################################################################################
