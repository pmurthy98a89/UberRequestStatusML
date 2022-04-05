# Uber Completion Stauts Machine Learning Project 
By: Praneel Murthy, Yousif Alkharraz, Ryan Hursh 

## Data Story
# Abstract:
For our final project, we are choosing to use Uber Requests dataset that consists of the pickup points, trip date, pickup time, and drop off time. We will use these features to discover any correlations between time of day, location, and request completion. Our model will attempt to predict the status of an Uber trip if it is completed or not. Our project can help Uber’s research department to pinpoint times with high uncompleted requests. Furthermore, it can help users find out the likelihood of a trip to be cancelled or uncompleted.   

As far as actual data analysis goes, we will begin by properly manipulating and cleaning the data. This includes removing unnecessary columns, dealing with missing data entries, adding clarifying columns to better model the time and dates, and acquiring important descriptive statistics to help us read the data easier. We will be using the SVM and Random Forest algorithms to help determine the status of the uber request based on certain predictors. 

# Feature Selection:
Our model features consist of the pickup points, trip date, pickup time, and drop off time to predict the response status. The reason our team chose the mentioned features is because the location, time of the day, traffic flow, and weekday or weekend contributes to the likelihood of having a trip completed or not. So, the features were chosen based on whether they make logical sense to use each individual ML method.  

Our predictors are pickup points, is_weekend, Req_TOD, and is_rushhour. Our response variable is the mapped status value of each request (I.e., 1 for complete, 0 for incomplete).  

We used bar charts to check for bias data.  There are no outliers because our predictors are based on date and time formats, putting restrictions on the possible values in their respective columns. In the same boat, those values will not be able to skew because they, again, are restricted to a 24-hour format and a verified date format. We represented missing data as null values to indicate that the uber request was not completed.  

# Dataset:
https://www.kaggle.com/datasets/anupammajhi/uber-request-data 
