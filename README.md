# Deeplearning_Case_Studies

# 1. Rain Prediction

## About the data :
        • The dataset contains about 10 years of daily weather observations from different locations across Australia. RainTomorrow is the target variable to predict. It means -- did it rain the next day, Yes or 
          No? This column is Yes if the rain for that day was 1mm or more.
## Context :
        • Predict next-day rain by training classification models on the target variable RainTomorrow.

## Data Dictionary:
        • predict the target variable Rain_Tomorrow the column which are the input are as follows:

               • DATE: the date if each day is provided to check the data is consistent, we can break date in day, month and year.
               • LOCATION: Albury, New castle, Richmode and other areas of Australia is covered
               • MIN TEMP: Min temperatura of each location is provided which helps to check the humidity of the environment
               • MAX TEMP: Max temperature is given to check the probablity of rain
               • RANFALL: Rainfall record is also given, there are som areas where 0.0 value is given so there were no rain happen about 10 years in that region.
               • EVAPORATION: Mostly the value of evaporation is NAN in different areas.
               • SUNSHNE: Sunshine value is mostly null in areas which the cloudy environment.
               • WIND GUST DIR: The direction od wind blowing is provided there.
               • WIND GUST SPEED: The speed of wind is also provided there.
               • WindDir9am : The direction of wind at specific time is there so the comparison b/w different times will help in analysis of Rain_Tomorrow.
               • WindDir3pm : Speed direction at 3pm
               • WindSpeed9am : Within Australia, wind speeds are generally presented in kilometres per hour. Thats why different time stamp wind speed is given there.
               • WindSpeed3pm : As above, due to change of wind speed per hour, this will help to predict the target variable.
               • Humidity9am : The humidity ranges b/w 6 hours in Australia.
               • Humidity3pm : As above, 6 hours change is provided for analysis
               • Pressure9am : Pressure rate per 6 hours is given
               • Pressure3pm : As it ranges or varies from 6 hours, the data will help to find accurate results.
               • Cloud9am : The weather changes about 6 hours
               • Cloud3pm : 6 hours gap in cloudy env data will helpful in prediction.
               • Temp9am : Temperature varien from north to south
               • Temp3pm : Temperature also varies fom 6 hours time stamp
               • RainToday : Rain Today is helpful to predict either its going to rai tomorrow.
               • RainTomorrow : Rain Tomorrow is our target variable to predict the rain in Australia by using above given features.
        
