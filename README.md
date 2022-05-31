# Ford GoBike System Exploration
This is the 3rd project in the **Udacity Data Analyst** Nanodegree program


## Dataset
The data consists of information regarding 183,000 rides made in a bike-sharing system covering the greater San Francisco Bay area. The data features include duration (secs) and others such as DateTime, customer type, gender, as well as some additional variables. The dataset can be downloaded from here [here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv)



## Summary of Findings
In the exploration, I found out that the average duration for all trips is about 500 seconds and most trips were on Thursdays and Tuesdays.
Weekends have the least trip records, although longer duration compares to other weekdays. One interesting thing I also found is the higher trip records for the 8th and 9th hours in the morning and the 17th and 18th hours in the evening. This can be linked to the rush during the two periods of the day. Most of the rides (>90) were taken by subscribers and over 70% of the total rides were taken by the male gender.

I found that normal customers spend much more duration on their trips than subscribers and females tend to ride for more duration than males. Only subscribers are allowed to share bikes on trips and trips with bike-sharing account for about 10% of the total rides.

User type seems not to affect the number of rides on any given day. And for any given day, customer user type tends to spend longer duration on their trips as compared to subscribers.


## Key Insights for Presentation
For the presentation, I focus on the frequencies of rides per hour, day, and user type while leaving out other variables. I start by checking out trip frequencies by hours and days of the week and the user type using seaborn countplot.

Afterwards,  I introduce each of the categorical variables one by one. To start, I use the boxplot plots of duration across days and user type. The other two categorical variables, days and user type, are covered afterwards, using point plots. I've made sure to use different color palettes for each quality variable to make sure is clear that they're different between plots.


### Blog Post
[on medium](https://tiamiyu.medium.com/ford-gobike-system-data-exploration-fb5b229d4106)
