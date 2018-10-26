# 2018-Arizona-Opportunity-Hack

[![Inventory Manager](https://img.youtube.com/vi/bbmFLjb4gn8/0.jpg)](https://www.youtube.com/watch?v=bbmFLjb4gn8)

## Inspiration
With Nonprofits feeding a lot of people every day becomes a lot of problems because there's a lot of manual work that needs to be done. It's our way of contributing to society be helping make their lives easier so that they can put more of their effort in managing. 


## What it does
It automates the process of managing inventory which is a very tedious job and is prone to human error while doing paper works. It reduces around 5-6 hours of their per month work. So, rather than sifting through loads of data the user can just upload the file through the user interface and see the results on the dashboard and also download a CSV file which gives the user all the aggregated reports for the months.

## How we built it
This app uses Spring Boot for backend and Angular 6 for front-end. The web application is deployed on Amazon Cloud EC2 instance and can be publically accessed.

## Accomplishments that we're proud of

It doesn't have a database layer, that saves the NPOs from hiring any DB administrator to maintain and look over the database. It uses sharding of files and segregating them according to categories.

## What we learned

We learned how to come up with a Minimum viable product in a short amount of time(a day). Working with a team of motivated individuals. 

## What's next for Insights-Mathews-Crossing

We are going to build it as a generic solution for other NPOs who go through the same pain of sifting through loads of data manually. Merge seamlessly with FoodBank Manager App, use S3 bucket on Amazon cloud to store the data.
