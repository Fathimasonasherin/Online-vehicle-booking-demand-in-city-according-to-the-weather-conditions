# Online-vehicle-booking-demand-in-city-according-to-the-weather-conditions
The objective is to combine historical usage pattern along with the open data sources like weather data to forecast the number of vehicle booking demand in a city. 

Data is randomly divided into train and test set. we must predict the total count of cabs booked in each hour covered by the test set, using the information available prior to the booking period. we need to append the train_label dataset to train.csv as ‘Total_booking’ column.

Please find the descriptions of the columns present in the dataset as below.

datetime - hourly date + timestamp

season - spring, summer, autumn, winter

holiday - whether the day is considered a holiday

workingday - whether the day is neither a weekend nor holiday

weather - Clear , Cloudy, Light Rain, Heavy

temp - temperature in Celsius

atemp - "feels like" temperature in Celsius

humidity - relative humidity

windspeed - wind speed 10 Total_booking - number of total booking
