# US-Energy-Timeseries
This is a time series analysis and forecasting project I have been working on. During the first stages of this Analysis I was attempting to find a solution with for determining null values within the given time series. 


###Part 1
Assuming that the information existed prior to the date of the last null value we should be able to fill in those values using an average estimator. I was interested in filling these values, but was not sure what might be the best approach since the data was changing over time either in a positive or negative direction and thought that perhaps using methods that I had previously used for classification such as filling with median or mean would not produce accurate results. While examining the the data and looking for a possible solution to filling these values I remembered that by using Annual Growth Rate I could determine missing values by determining the rate of change between the given values then using the increase or decrease formula depending on the direction of the values given. 


