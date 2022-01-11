# Project: Ford GoBike Data Exploration 2019

## Intro
Data has 183412 rows and 16 columns. Data includes information about users, bike
stations, duration of the rides. Information about users contains: user type (customer or
subscriber), birth year, and gender.

The main focus on user-related features: user_type, member_birth_year,
and member_gender. Features duration_sec, star - end time will help investigate users'
behavior.

The main goal is to find demographic values of the data set and investigate how users
use the service.

## Needs of this project
- Wrangling: gathering, assessing and cleaning data
- Exploratory Data Analysis: univariate, bivariate and multivariate

## Summary
Original data has 183412 rows and 16 columns. During assessment were detected four
quality and three tidiness issues. After fixing all issues shape of the data set contains
174582 rows and 12 columns.
In section one was investigated individual variables and found out that the average user
of Ford GoBike is a male of 32-34 years old, a subscriber. The less popular days of the
week are Saturday and Sunday, but in section two, it was discovered that weekend has
the most extended ride duration.

## Key Insight
- The median ride is 511 seconds, and the average ride is 704 seconds. Durations
of rides take on a vast range of values, from 61 seconds at the lowest to 84548
seconds at the highest.
- The major part of each gender is the "Subscriber" user type. Also, males make
up 75% of all users.
- Users in 30 years made the most significant number of long rides.
- The "Customer" average ride duration is 1310 seconds, and the
average "Subscriber" duration of ride equals 640 seconds.

## Limitation
The main limitation of the data set is that it is only one month data. We can't make a
conclusion by month and seasonality based on this data. Also, I would like to see more
users' data; each user, each ride, cost of a ride. That data would be convenient for
business decisions.
