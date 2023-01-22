# Communicate-Data-Findings
>Fifth project in Udacity Data Analyst NanoDegree

# Ford GoBike System Data Exploration
## by Rahaf Aljehani


## Dataset

> I selected Ford GoBike System dataset for analysis, it includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. This data contains 183412 individual rides with 16 features, these features include duration variables such as:duration in sec, start time and end time, also include users information such as:user type and gender.

>To sum up the previous steps, I started with preliminary wrangling. To understand the Ford GoBike System database, change data types of variabls, and make sure there is no too many missing or duplicated values. Then, I decided to focus on trip duration feature as my feature of interest. I investigate the trip duration feature with multiple other features, whether as a univariante exploriation, bivariate explorations, or multivariate explorations.


## Summary of Findings

> Here is the list of all the findings: 
### Univariate Exploration
1. Distribution of trips duration has right skewed (long talied). So,I used a log transformation on the x-axis, after log transformation most of the trips are between 100 and 2500 seconds with one peak around 650 seconds approximately.
2. Most of the users is subscriber.
3. Most of the users is male.
4. Most of the users didn't share bike for all trip.
5. Most of the users' ages fall between 18 and 40 years approximately.
6. When we compared between distribution of start stations and end stations we got distribution of start stations and end stations is very similar.

### Bivariate Exploration
1. Customers trip duration take longer than subscribers trip duration.
2. Female users trip duration take longer than male users trip duration.
3. The users who spend more trip duration are between the ages of 18 and 40.
4. On Saturday and Sunday, the duration of the trips is longer than the rest of the week.
5. Users who don't share a bike have a longer trip duration than those who share bike for all trip.
6. On Thursday, the number of customers and subscribers is more than the rest of the week.
7. Most of customers and subscribers are male.
8. Most of customers and subscribers they don't share a bike for all trip.

### Multivariate Exploration
1. The relationship for trip duration, user age and user type is very similar to the relationship for trip duration and user age, but the subscribers trip duration is more than the customers trip duration although both have the same user age ratio.
2. The relationship for trip duration, user age and user gender is very similar the relationship for trip duration and user age, but the males trip duration is more than the females trip duration although both have the same user age ratio.
3. In general, customer users have a longer trip duration throughout the week than subscriber users.
4. On Saturday and Sunday, the duration of the trips was longer than the rest of the days of the week for both the subscribers and customers users.
5. In general, females users have a longer trip duration throughout the week than males users.
6. On Saturday and Sunday, the duration of the trips was longer than the rest of the days of the week for both the females and males users.


## Key Insights for Presentation

> I decided to focus on trip duration feature as my feature of interest.
The following list summarizes the main findings throuhout my investigation:
1. Distribution of trips duration has right skewed (long talied). So,I used a log transformation on the x-axis, after log transformation most of the trips are between 100 and 2500 seconds with one peak around 650 seconds approximately. 
2. The number of trips increases on Thursday, and the number of trips decreases on Saturday and Sunday.
3. On Saturday and Sunday, the duration of the trips is longer than the rest of the week.
4. The users who spend more trip duration are between the ages of 18 and 40.
5. In general, customer users have a longer trip duration throughout the week than subscriber users.
6. On Saturday and Sunday, the duration of the trips was longer than the rest of the days of the week for both the subscribers and customers users.
7. In general, females users have a longer trip duration throughout the week than males users.
8. On Saturday and Sunday, the duration of the trips was longer than the rest of the days of the week for both the females and males users.

