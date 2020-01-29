# Accelerometer & Pumps
Research &amp; Development Data Science

Exercise 1: You are given a one-second sample of time-series data in tdms format named ‘ex1.tdms’, which were obtained from sensors attached to a pump. Write a short documentation (max 2 pages) to explain the data to other data scientists and management team. In particular, explain processing steps that you decided to perform on the data, their motivations and results. 

Exercise 2: One of the objectives that we want to accomplish using data such as given in Exercise 1 is to search for possible anomaly (in the sense of unexpected change in machine state due to e.g. parts breakdown event; we assume that sensor data are perfectly clean of artifacts) in the dataset and report the time during which the anomaly occurs. Propose a process to accomplish such system, including details about preprocessing steps, and other modelling choices and describe it in a short documentation (max 2 pages). 
 
Bonus: write a code/pseudocode implementation of your idea. 
Exercise 3: The objective of this exercise is to train a machine learning model. The data used in this exercise was gathered from a test pump in a lab. The pump was put into 4 different states (normal operation, pump cavitation, shaft misalignment, or low flow) while gathering data. After collecting all of the raw sensor values, Flowserve Data Scientists performed feature engineering on the data to obtain a training matrix (X) and classification vector (y). It is encouraged that no further feature engineering is performed on the data set. 
 
In a folder labeled ‘ex3’, you will find the labelled training examples in subfolder ‘training_data’ that contains an X matrix and a y vector. Your objective is to train a machine learning model using this data. X is an m by n data matrix; where m is the number of data points and n is the number of different features that resulted from performing feature engineering. Each row of data in X corresponds to 1 second elapsed. y is an m by 1 classification vector; where m is the classification identifier for each data row in X. The mapping is as follows: 1 = Normal Operation 2 = Cavitation 3 = Misalignment 4 = Low Flow
