# Bike_Sharing_Demand_Prediction

![image.png](https://d9hhrg4mnvzow.cloudfront.net/www.slugbikelife.org/giveaway/234e4595-e-bike-motion.gif)

## Introduction 📘
Electric bike renting is a growing trend in many cities around the world. It is a convenient and eco-friendly way to get around town. Electric bikes are powered by a battery and can reach speeds of up to 25 mph. They are easy to use and require no license or registration. Renting an electric bike is a great way to explore a city without having to worry about parking or traffic. It is also a great way to reduce your carbon footprint and help the environment, it would be interesting to perform data analysis on the data to obtain valuable insights.

## Problem Description 🤔  
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

### The contents of Seoul Bike Data are:
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented 
per hour and date information.

* **Date** - year-month-day
* **Rented Bike coun**t - Count of bikes rented at each hour
* **Hour** - Hour of he day
* **Temperature** - Temperature in Celsius
* **Humidity** - %
* **Windspeed** - m/s
* **Visibility** - 10m
* **Dew point temperature** - Celsius
* **Solar radiation** - MJ/m2
* **Rainfall** - mm
* **Snowfall** - cm
* **Seasons** - Winter, Spring, Summer, Autumn
* **Holiday** - Holiday/No holiday
* **Functional Day** - NoFunc(Non Functional Hours), Fun(Functional hours)

## The series of steps followed in this project 📃

    1. Importing Packages
    2. Reading Data
    3. Explore the structure of the Datasets
    4. Data Cleaning
    5. Exploratory Data Analysis (EDA)
    6. Data Transformation
    7. creating ML Models
	
## The tools that are going to be used for this project would be 💾
   
    1. Numpy 
    2. Pandas
    3. Matplotlib
    4. Seaborn
    5. Sklearn
    6. Datetime
   
**which I have learnt from the course.**

## Algorithm that used in this project are 🔣

    1. Linear regression
    2. Gradient Boosting regression
    3. Random forest regression

## Conclusion ✌

**Comparing to three Models the Random Forest algoritham has highest R2 Score 98 % and 91 % respectively for Train and Test datas and Gradient Boosting algorithm also had good R2 Score 87 % and 86 % respectively for Train and Test datas then, there is no overfting found in all these models. The Feature importance of both models are slightly differnt from each others. So better result We can deploy these models.**

* The demand for rented bikes is higher from months 4 to 10 compared to other months, these months fall during the summertime.

* Use of rental bike count rising during business hours ( 7 to 9 and 17 to 19 ), these are consider as peak hours.

* During none functioning day bikes are seems not rented.

* Performance of the rented bike count during the winter is relatively low, and the bike counts are much raised during the summer.

* When compared to holidays, bike counts are significantly higher on non-holiday days; this may be because of office hours
