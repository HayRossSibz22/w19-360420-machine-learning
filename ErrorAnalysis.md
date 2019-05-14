#kNN Machine Learning Error Analysis Report

###Hayden Ross and Ashley LongLastName

###Professors Sameer Bhatnager and Jean-François Brière

###Intro to Computer Programming in Engineering and Science

###360-420-DW Section 02

###May 14 2019

###Distributions of Model Accuracy: Confidence in Model

Why do we get a different accuracy each time we run the classification model?

In DataSet.java, lines 148 to 150 explain why the accuracy each time the classification model is run is different. In java, the class method '.shuffle' from the 'Collections' class accesses different elements randomly from a given String. Thus, each time we cut the data set, we work with a different section of data. This affects the accuracy of the overall results.

How much does performance vary on unseen data?
Performance varies marginally. Most results are only different at the fourth decimal place. The standard deviation is therefore very small.

The mean is 0.069559

STD: 1.735 x 10^-4

What is a sensible baseline against which we should compare our model's performance?
An ideal baseline to compared our model’s performance to is random. There should be logic, though. Like depending on all the data that is being accumulated, it should make sense. For example being close to zero or being positive. The baseline can be simple and basic, based on the data that we have. 
