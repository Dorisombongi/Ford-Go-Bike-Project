# FordGoBike Data Exploration and Key Insights
## by DORIS B OMBONGI

## Investigation Overview

> In this investigation, I wanted to look at the characteristics of bike trips that could be used to predict trip duration. The main focus was on age and user type.

## Dataset

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. The dataset consists of information regarding 183412 bike trips including trip durations in seconds, start time, end time, start station id, start station name, start station latitude, start station longitude, end station id, end station name, end station latitude ,end station longitude, bike id, user type, member birth year, member gender and bike share for all trip columns containing each trip information. The dataset can be downloaded from 'https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv'


## Summary of Findings

> In the exploration regarding the main variable of interest(trip duration). I found that there was a strong relationship between trip duration and age. Trip duration also is most likely to depend on user type and bike share, but it less likely dependant on gender.
> In multivariate exploration, i found out that males have the most number of longer trip durations but all younger riders in all genders are likely to have longest trips, younger riders both customers and subscribers are likely to have longer trips compared to older people even though subscribers had the most number of longer trip durations and younger riders who shared their bikes are likely to have longer trips compared to older people while the ones who did not share their bikes have almost the same trip duration distributed in all ages even though most riders did not share their bikes.
> In the exploration regarding other variables, I also looked into relationship between gender and age, bike share and age & gender and user type. It showed that other gender are likely to be older people, older riders are not likely to share their bikes and subscribers are likely to be the most riders in all genders.

## Key Insights for Presentation

> In the presentation I focus on the relationship between bikes trip duration and age and between trip duration and member_gender (customers and subscribers).
> I start with a histogram with the distribution of trip count in the age variable and a barchart with the distribution of trip count in the user type.
> Followed by the distribution of trip duration vs age and distribution of trip duration for each user_type.
> Finally I present a FacetGrid of trip duration in minutes by age and user type which shows how the threes variables are related and it shows to scatterplots for customers and subscribers.
