# Amazon Forecast No-code-workshop
No code workshop to experiment on Amazon Forecast

Introduction: Amazon Forecast is a machine learning service that provides prediction based on time series data provided by AWS.

## Region selection
Please check with your instructor about the regions where you will be working with this hands-on. You can change it by selecting the place name in the upper right of the screen:

[[Picture]]
 

## Download data for learning
https://bit.ly/2Oof8qe
This CSV file includes power consumption data for individual household. Here's a snippet:
 
 [[picture]

In this hands-on workshop, future power consumption will be predicted based on this time series data. Amazon Forecast can process any time series data, so sales data, inventory consumption data, etc. can also be used.

## Creating an S3 bucket
Amazon Forecast imports the training data from any S3 bucket: let's create an S3 bucket to store the CSV file downloaded earlier.

1. Access the S3 management console by typing S3 as shown below:
 
2. Press [Create Bucket]
 
3. Enter an appropriate name in [Bucket Name]

[[picture]

The S3 bucket must have a reasonably long name because it must be unique across all AWS users. Specify the same region as the region in which you will be working on Amazon Forecast.
