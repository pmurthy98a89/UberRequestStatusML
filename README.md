# Uber Completion Stauts Machine Learning Project 
By: Praneel Murthy, Yousif Alkharraz(https://www.linkedin.com/in/yousif-alkharraz/), Ryan Hursh (https://www.linkedin.com/in/ryanhursh-/) 

## Data Story
# Abstract:
Our team chooses the Uber Requests dataset for our final project, consisting of pickup points, trip date, pickup time, and drop-off time. We will use these features to discover correlations between the time of day, location, and request completion. Our model will attempt to predict the status of an Uber trip if it is completed or not. Our project can help Uber’s research department to pinpoint times with high uncompleted requests. Furthermore, it can help users determine the likelihood of a canceled or incomplete trip.   

As far as actual data analysis goes, we will begin by manipulating and cleaning the data. This includes removing unnecessary columns, dealing with missing data entries, adding clarifying columns to better model the time and dates, and acquiring critical, descriptive statistics to help us read the data easier. Things like outliers and distributions will not need to be applied to this dataset with categorical type data. We will be using the SVM and Random Forest algorithms to help determine the status of the uber request based on specific predictors.  

# Feature Selection:
Our model features consist of the pickup points, trip date, and pickup time to predict the response status. Our team chose the mentioned features because the location, time of the day, traffic flow, and weekday or weekend contribute to the likelihood of having a trip completed or not. So, the features were chosen based on whether they make logical sense to use in Machine language or not.  

The trip date and pickup time feature needed to be changed from time and date to categorical data columns. The trip date column was transformed to 0 for weekends and 1 for weekdays. Also, the pickup time column was converted to the time of the day (morning, afternoon, afternoon, evening, and night). In addition, another column was added to represent if it was at rush hour or not. The reason behind converting them is to make them compatible with the model.  

Our predictors are pickup points, is_weekend, Req_TOD, and is_rushhour. Our response variable is the mapped status value of each request (I.e., 1 for complete, 0 for incomplete).   

We used bar charts to check for biased data. There are no outliers because the type of predictors are categorical data and do not have outliers because outliers are continuous data. In the same boat, those values will not be able to be skewed because they, again, are categorical data. However, the distribution is analyzed by bar charts to check for equality and fairness. Central tendency is related to continuous data where the distribution affects the mean, median, and so on, but our data is discrete. We represented missing data as null values to indicate that the uber request was not completed. This means that null values cannot be dropped as they are still crucial data points. 

# Dataset:
https://www.kaggle.com/datasets/anupammajhi/uber-request-data 
