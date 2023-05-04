# US-Energy-Timeseries

![Alt text](https://github.com/lifeofbaka/US-Energy-Timeseries-Analysis-and-Forecasting/blob/main/graphs%20(1).gif)

This is a time series analysis and forecasting project I have been working on which includes Visualizations for several Energy categories in the United States. During the first stages of this Analysis I was attempting to find a solution for determining null values within the given time series. After cleaning the data I used the ARIMA model to train and create predictions.


### Part 1
Assuming that the information existed prior to the date of the last null value we should be able to fill in those values using an average estimator. I was interested in filling these values, but was not sure what might be the best approach since the data was changing over time either in a positive or negative direction and thought that perhaps using methods that I had previously used for classification such as filling with median or mean would not produce accurate results. While examining the the data and looking for a possible solution to filling these values I remembered that by using Annual Growth Rate I could determine missing values by determining the rate of change between the given values then using the increase or decrease formula depending on the direction of the values given. 

### Part 2 
Using the ARIMA Model I was able to create a prediction model of the changes in values over time. I automated this process and returned predictions for 127 different columns of the dataset to show how each area of US energy may be affected within the next 20 years in a forecast using the the trained model. Overall this provided accurate results, but there were some issues due to the differences between columns that can be corrected by tuning the model based of the results and parameters. In order to make this process more user friendly the notebook uses the PYWidget package with allows a GUI selection of the column data that should be accessed for training and predictions.  


