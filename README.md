# Amazon Forecast tutorials
*Experiment on Amazon Forecast with the console or the APIs*

Amazon Forecast is a machine learning service that provides prediction based on time series data provided by AWS. In this repository, you will find a tutorial to walk you through an energy consumption use case with two different methods:

1. For the first method, you will only use the service console and this will be 100% no-code: use this [markdown file](forecast-with-console.md) to follow along.
2. For the second method, you will fire up a SageMaker Notebook Instance and perform exactly the same process by using the Amazon Forecast API as documented [here](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/forecast.html) (for datasets and models management features) and [here](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/forecastquery.html) (for the query service): run [this notebook](forecast-with-api.ipynb) to dive deeper in these APIs.
