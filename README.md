---
title: "Cyclistic Bike Study"
author: theepeekaa
date: "`r format(Sys.time(), '%d %B, %Y')`" 
output: html_document
---

### About the company:
In 2016, Cyclistic launched a successful bike-share oﬀering. Since then, the program has grown to a ﬂeet of 5,824 bicycles that are geotracked and locked into a network of 692 stations across Chicago. The bikes can be unlocked from one station and returned to any other station in the system anytime.

Until now, Cyclistic’s marketing strategy relied on building general awareness and appealing to broad consumer segments. One approach that helped make these things possible was the ﬂexibility of its pricing plans: single-ride passes, full-day passes, and annual memberships. Customers who purchase single-ride or full-day passes are referred to as casual riders. Customers who purchase annual memberships are Cyclistic members.

Cyclistic’s ﬁnance analysts have concluded that annual members are much more proﬁtable than casual riders. Although the pricing ﬂexibility helps Cyclistic attract more customers, Moreno believes that maximizing the number of annual members will be key to future growth. Rather than creating a marketing campaign that targets all-new customers, Moreno believes there is a very good chance to convert casual riders into members. She notes that casual riders are already aware of the Cyclistic program and have chosen Cyclistic for their mobility needs.

Moreno has set a clear goal: Design marketing strategies aimed at converting casual riders into annual members. In order to do that, however, the marketing analyst team needs to better understand how annual members and casual riders diﬀer, why casual riders would buy a membership, and how digital media could affect their marketing tactics. Moreno and her team are interested in analyzing the Cyclistic historical bike trip data to identify trends.

### Scenario:
You are a junior data analyst working in the marketing analyst team at Cyclistic, a bike-share company in Chicago. The director of marketing believes the company’s future success depends on maximizing the number of annual memberships. Therefore, your team wants to understand how casual riders and annual members use Cyclistic bikes diﬀerently. From these insights, your team will design a new marketing strategy to convert casual riders into annual members. But ﬁrst, Cyclistic executives must approve your recommendations, so they must be backed up with compelling data insights and professional data visualizations.

### Business Task:(ASK)
1.	How do annual members and casual riders use Cyclistic bikes differently?

### Tools used:

R for Data Cleaning and Tableau for Visualization

### Prepare and Process:

* Install the tidyverse, lubridate and ggplot2 packages for data cleaning
* Import the last 12 months [data set](https://divvy-tripdata.s3.amazonaws.com/index.html)
* Data cleaning and Combining to a Single data set
* Adding new columns required for the analysis - Ride length, Date, Month, Year, and Week of the day, mean of the ride_length by months, max of ride_length by months

### Analyze:

#### Tool: Tableau

#### Casual Riders (Count) by each month:
<img width="491" alt="image" src="https://user-images.githubusercontent.com/84039199/155821661-bc16da69-4a62-4ab3-9c3e-8312209748e2.png">

#### Annual Members (Count) by each month:
<img width="494" alt="image" src="https://user-images.githubusercontent.com/84039199/155821793-56203423-2e1e-4a26-9478-18b8f9815e5e.png">

#### Day of the Week and Casual riders:
<img width="490" alt="image" src="https://user-images.githubusercontent.com/84039199/155821830-fddf99ff-6fd9-4097-a051-b8718b5749b8.png">

#### Day of the Week and Annual members:
<img width="503" alt="image" src="https://user-images.githubusercontent.com/84039199/155821891-0acd4b14-3d98-48ab-ba0e-63c8e191432d.png">

#### Average Ride length by Members/Casual:
<img width="486" alt="image" src="https://user-images.githubusercontent.com/84039199/155821935-8c5c1047-acc4-4fb3-95f5-5fd6f3bd42e7.png">

#### Average Ride length by Members/Casual and month:
<img width="661" alt="image" src="https://user-images.githubusercontent.com/84039199/155822028-a8812220-7900-4bfb-9a61-57380af5ae03.png">


### Key Findings:

* Annual members has more rides compared to the casual riders
* While casual riders has more ride length than Annual members 
* Casual riders rides more on the weekends - Saturday and Sunday
* Casual riders rides more in August, September, and October (Considering the Weather)

### Recommendations:
* Promote the Cyclistic Bike Program to the casual riders about the annual membership
* Come up with reasonable pricing and long ride length duration for the annual membership
* Price up 10 to 20 bucks than the usual price for the casual riders so that they may consider the annual membership and its benefits
* Collaborate with the tiktok stars about the annual membership 

