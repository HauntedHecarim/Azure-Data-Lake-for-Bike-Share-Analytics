# Azure-Data-Lake-for-Bike-Share-Analytics

Project Overview
In this project, you'll build a data lake solution for Divvy bikeshare.

Divvy is a bike sharing program in Chicago, Illinois USA that allows riders to purchase a pass at a kiosk or use a mobile application to unlock a bike at stations around the city and use the bike for a specified amount of time. The bikes can be returned to the same station or to another station. The City of Chicago makes the anonymized bike trip data publicly available for projects like this where we can analyze the data.

Since the data from Divvy are anonymous, we have generated fake rider and account profiles along with fake payment data to go along with the data from Divvy. The dataset looks like this:

![image](https://github.com/HauntedHecarim/Azure-Data-Lake-for-Bike-Share-Analytics/assets/10834793/d8df0e7d-3960-4d68-af0b-6f1cbc6518b8)

This image represents the data model for the dataset based on the Divvy Bikeshare data. The tables include: Rider, Account, Payment, Trip, and Station.
Relational ERD for the Divvy Bikeshare Dataset (with fake data tables)
---

The goal of this project is to develop a data lake solution using Azure Databricks using a lake house architecture. You will:

  Design a star schema based on the business outcomes listed below;
  Import the data into Azure Databricks using Delta Lake to create a Bronze data store;
  Create a gold data store in Delta Lake tables;
  Transform the data into the star schema for a Gold data store;
  
**The business outcomes you are designing for are as follows:**
1. Analyze how much time is spent per ride
2.   Based on date and time factors such as day of week and time of day
3.   Based on which station is the starting and / or ending station
4.   Based on age of the rider at time of the ride
5.   Based on whether the rider is a member or a casual rider
6. Analyze how much money is spent
7.   Per month, quarter, year
8.   Per member, based on the age of the rider at account start
9. EXTRA CREDIT - Analyze how much money is spent per member
    Based on how many rides the rider averages per month
    Based on how many minutes the rider spends on a bike per month
