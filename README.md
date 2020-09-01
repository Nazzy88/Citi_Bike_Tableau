# Citi_Bike_Tableau
Aggregate Data From the Citi Bike Trip History Logs to Build a Data Dashboard, Story, or Report Using Tableau

### Tableau Public Website
https://public.tableau.com/profile/nazia5720#!/vizhome/CitiBikeAnalysis_15988533209510/BikeStory

## Background

![Citi-Bikes](Images/citi-bike-station-bikes.jpg)

Congratulations on your new job! As the new lead analyst for the [New York Citi Bike](https://en.wikipedia.org/wiki/Citi_Bike) Program, you are now responsible for overseeing the largest bike sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicize and improve the city program.

Since 2013, the Citi Bike Program has implemented a robust infrastructure for collecting data on the program's utilization. Through the team's efforts, each month bike data is collected, organized, and made public on the [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have a number of questions on the program, so your first task on the job is to build a set of data reports to provide the answers.

## Task

**Your task in this assignment is to aggregate the data found in the Citi Bike Trip History Logs and find two unexpected phenomena.** 

How many trips have been recorded total during the chosen period?
* There are over 12 million for the month of July years 2013-2020.

By what percentage has total ridership grown?
* It varies from year to year in July. The biggest increase was from 2015 to 2016 with a 27.12 % increase.  Currently there is a dip from 2019 to 2020 with a loss of 3.45%.  This could be due to Covid-19.  To be honest I thought the dip would be more since everyone is quarantining.  However, it looks like people are taking sanitary precautions such as gloves in order to rent the bikes.  OR they could be using their own bikes and using Citi Bike’s locks.   

How has the proportion of short-term customers and annual subscribers changed?
* When I did look at the month of July from 2013 to 2020.
It looks like there was a huge growth in subscribers in 2014 by 27.12%, it looks like people who were customers in 2013 became subscribers in 2014, that is why there is a dip by -31.93 for customers in 2014.  It looks like there is a big increase in customers from 2014 to 2015 by 51.48%.  That being said there is only a 6.54 % in 2015 for subscribers.  From 2016 to 2017 there seems to be a fruitful year since there is 29.63% increase in customer and a 25.09% increase in subscribers.  The year 2019 to 2020 you will see an interesting increase in 52.07% in customers and a dip by -15.09%.  This could be because the consumer is still concerned about quarantining and doesn’t want to use public transportation such as the subway.  Also, there is a drop in subscriptions due to unemployment and making commitments during a financial chaotic time.    

What are the peak hours in which bikes are used during summer months?
* The peak hours for July Start Times are 8am,5pm, and 6pm.
* The peak hours for July End Times are 8am, 9am, and 6pm.

Today, what are the top 10 stations in the city for starting a journey? (Based on data, why do you hypothesize these are the top locations?)
* 1.	West St. Chambers St
* 2.	E 17 St & Broadway
* 3.	Pershing Square North
* 4.	12 Ave & W 40th St
* 5.	8 Ave & W 31 St
* 6.	W 21 St & 6 Ave
* 7.	Broadway & E 22 St
* 8.	Broadway & E 14 St
* 9.	Broadway & W 60 St
* 10.	W 20 St. & 11 Ave

Today, what are the top 10 stations in the city for ending a journey? (Based on data, why?)
* 1.	West St. Chambers St
* 2.	E 17 St & Broadway
* 3.	12 Ave & W 40 St
* 4.	Pershing Square North
* 5.	W 21 St & 6 Ave
* 6.	Broadway & E 22 St
* 7.	8 Ave & W 31 St
* 8.	Christopher St & Greenwich St
* 9.	Broadway & E 14 St


Today, what are the bottom 10 stations in the city for starting a journey? (Based on data, why?)
* 1.	NYCBS Depot -PIT
* 2.	Kiosk in a box Deployment
* 3.	8D OPS 01
* 4.	SSP Tech Workshop
* 5.	Brook Ave. & E 157 St
* 6.	NYCBS Depot – FAR
* 7.	E156 & Brook Ave
* 8.	Gowanus Tech Station
* 9.	Prospect Ave. Longwood
* 10.	8D Mobile

Today, what are the bottom 10 stations in the city for ending a journey (Based on data, why?)
* 1.	8D Mobile 01
* 2.	8D QC Station 01
* 3.	Baldwin at Montgomery
* 4.	Bike Mechanics at Riis Room A
* 5.	Bike Mechanics at Riis Room B
* 6.	Brunswick St
* 7.	Columbus Dr at Exchange Pl
* 8.	Dey St
* 9.	Fairmount Ave
* 10.	Harborside

Today, what is the gender breakdown of active participants (Male v. Female)?
* Males use the bikes more in 2020 by 47%.  Also, again in 2019 by 62%.    However, Females have a higher duration of bike trip if they do use service.  There is a sufficient amount of riders that don’t share their gender either for both years so the numbers are subjective. 

How effective has gender outreach been in increasing female ridership over the timespan?
* It looks like growth was the most in 2016 by 36.90 % and in 2017 by 34.99 %.  After that it dropped off to the teens for the rest of the years till 2020.

Which bikes (by ID) are most likely due for repair or inspection in the timespan?
* 	16734
* 	16808
* 	18275
* 	16763
* These IDs were mentioned due to having the longest trip duration. 
