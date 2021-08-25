---
layout: post
title: Ford GoBike System Data
date: 2021-08-15 23:18 +0800
---
# Data Visualiztion
![FordBike](https://live.staticflickr.com/936/29927098378_86fc9a6f54_b.jpg)

# Investigation Overview
This presentation summarizes the results of exploratory data analysis preformed on the Ford Go-Bike System Data.
This project is a part of Udacity Data Analysis Nanodegree supported by Misk Academy.

# Dataset Overview
Ford Go-Bike is a regional public bicycle sharing system in the San Francisco Bay Area, California.
This dataset represents the data for the trips made using Ford Go-Bike during February of 2019.

# Number of Rides for different Start Hours
The highest frequencies of rides are for those starting around 8 am and 5 pm. These are trips take by nine-to-fivers. This is more supported by looking at the number of rides during different week days.

![img1](https://mahmoudsaziz.files.wordpress.com/2021/02/image.png)
![img2](https://mahmoudsaziz.files.wordpress.com/2021/02/image-1.png)

# Trip duration and starting hour
Comparing trip duration to starting hour, When limiting the trip duration to 20 minutes representing 90% of the trips, the effect of nine-to-fivers rush hours is clear.
![img3](https://mahmoudsaziz.files.wordpress.com/2021/02/image-2.png)

# Trip duration and user type
Subscriber’ trips are clearly shorter than the those of the customers.

![img4](https://mahmoudsaziz.files.wordpress.com/2021/02/image-3.png)

# Trip duration and user type
That’s because these are mostly work related trips and time is a factor here. This can be visualized by plotting number of trips during different hours for different user types.

![img5](https://mahmoudsaziz.files.wordpress.com/2021/02/image-4.png)

# Start hour, user type and average trip duration
Customers have less variation in average trip duration during the day. while the effect of rush hours are clear on average trip duration of subscribers.

![img5](https://mahmoudsaziz.files.wordpress.com/2021/02/image-1-1.png)

# Start hour, user gender and average trip duration
There seem to be no change in the patterns, although the mean values are larger for females.

![img5](https://mahmoudsaziz.files.wordpress.com/2021/02/image-7.png)


