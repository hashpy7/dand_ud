# Bike rental services analysis with Ford GoBike dataset
## by Ayush Umrao

## Dataset

> The data consists of information regarding for GoBike rental services, including
age, timeframe, gender, station, and others. The dataset can be found in Ford GoBike website.  
Dataset: (https://s3.amazonaws.com/fordgobike-data/index.html)  
The data consisted of 19 different variables such as age, gender, weekday, time and others. It contains 3.31 million rides. Ages in dataset from 18 to 56 takes 95% of the users in dataset. There were users more than 100 years old. So, we have removed users having age more than 56 years as part of the cleaning up process.  


## Key Insights for Presentation

> There was one unusal distribution for the member birth year, which in some cases was dated before 1900 and customers having age of 141. This surely should be an entry error. Since 95% of the members are between 17 and 56 years, I removed users older than 56.
During winter months, there is decrease in bike rides. The bikes are used mostly on weekdays and around 8-9 am and 5-6 pm. If we consider the duration of trips, its unusual that some of the trips stretch upto 50 hours.
Adding user type in the mix showed different usage patterns between the two types of users. I believe the customers are users that rent the bike when absoutely necessary, as tourists or for leisure purpose whereas subscribers mostly use this service for their daily commute which should generally be a short distance and therefore less lengthy.
Plotting a heatmap of when bikes are high in demand throughout the day on each weekday shed a new light on the customers behaviour. People use this service on weekdays more than weekends and 8am to 5pm are the peak hours.
Percentage of subscribers is almost 88.35% and customers is almost 11.65%. Subscribers’ average trip duration is around 6 minutes. Customers’ average trip duration is around 26 minutes. 90% of bike rides take place on weekday. The peak bike rides time for all members is around commute time.
