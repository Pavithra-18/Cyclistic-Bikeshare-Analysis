# Introduction:
This case study is about Bikeshare Data analysis for a fictional company called **Cyclistic** and is a part of **Google Data Analytics Professional Certificate**.

**About the Company**:
In 2016, Cyclistic launched a successful bike-share offering. Since then, the program has grown to a fleet of 5,824 bicycles that are geotracked and locked into a network of 692 stations across Chicago. The bikes can be unlocked from one station and returned to any other station in the system anytime.
Until now, Cyclistic’s marketing strategy relied on building general awareness and appealing to broad consumer segments. One approach that helped make these things possible was the flexibility of its pricing plans: single-ride passes, full-day passes, and annual memberships. Customers who purchase single-ride or full-day passes are referred to as casual riders. Customers who purchase annual memberships are Cyclistic members. Cyclistic’s finance analysts have concluded that annual members are much more profitable than casual riders. Although the pricing flexibility helps Cyclistic attract more customers, Moreno believes that maximizing the number of annual members will be key to future growth. Rather than creating a marketing campaign that targets all-new customers, Moreno believes there is a very good chance to convert casual riders into members. She notes that casual riders are already aware of the Cyclistic program and have chosen Cyclistic for their mobility needs.

**Scenario**:
The director of marketing believes the company’s future success depends on maximizing the number of annual memberships. Therefore, the Marketing team wants to understand how casual riders and annual members use Cyclistic bikes differently. From these insights, the team will design a new marketing strategy to convert casual riders into annual members. But first, Cyclistic executives must approve my recommendations as Junior Data Analyst, so they must be backed up with compelling data insights and professional data visualizations.

**Stakeholders and their roles**:
**Cyclistic**: A bike-sharing program featuring more than 5,800 bikes and 600 docking stations. Cyclistic differentiates itself from other companies by also offering reclining bikes, hand tricycles, and cargo bikes, making bike-share more inclusive for people with disabilities and riders who cannot use standard two-wheelers. The majority of riders choose traditional bicycles; about 8% of riders use assisted options. Cyclists are more likely to cycle for leisure, but around 30% use it to commute to work every day.
**Lily Moreno**: As a Marketing Director and Manager, Moreno is responsible for the development of campaigns and initiatives to promote the bike share program. This may include email, social media, and other channels.
**Cyclistic marketing analytics team**: A team of data analysts responsible for collecting, analyzing, and reporting on data that helps guide Cyclistic's marketing strategy. 
**Cyclistic's executive team**: The highly detail-oriented executive team will decide whether they approve the recommended marketing program.

**Problem Statement**:
Design marketing strategies to convert casual riders into annual members. 
•	Identify the factors that differentiates casual riders from members. 
•	Identify the factors that would make the casual riders buy a membership.
•	Identify the trends for best results

In this case study, the following data analysis processes were followed:
1. Ask
2. Prepare
3. Process
4. Analyze
5. Share
6. Act

**Ask**:
* What is the ride length based on the user type?
* What is the total no. of users in each user type based on type of the ride, day of week?
* What is the average duration in minutes based on the user type?

**Prepare**:
-For this case study, I have used 12 months’ data from last year (2023) from the link: https://divvy-tripdata.s3.amazonaws.com/index.html
-The data is structured ie., Organised data.
-The data has been made available by Motivate International Inc. under this license.

I have used Python to pre-process (clean) the data and visualize it. 

**Process**:
Pre-processing the data is a crucial phase before proceeding with analysis to derive insights. The following tasks were performed in this phase:
* Merging separate month CSV files into a single file
* Changing data type of started at and eneded at columns to date time type
* Checking for duplicates and removing them
* Removing null values

**Analyze** & **Share**:
From the analysis, the following observations were found:
* Members never used docked bikes
* Members used classic bikes and electric bikes more than the casual riders
* In contrary to members, maximum number of casual riders used the bikes on weekends rather than weekdays
* Casual riders seem to be taking 2 times longer rides in contrary to members.
* Most of the casual riders used the bikes in summer. Surprisingly, maximum memebers used the bikes in Autumn as compared to spring in contrary to casual riders.

**Act**:
Increase the ride
