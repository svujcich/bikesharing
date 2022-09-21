# Overview
Bike sharing is a trend in which individuals rent and use bicycles for a fee.  In this project, Tableau is used to generate visualizations to analyze data from a bike share in New York City during the month of August. By exploring bike usage trends in relation to user demographics, this project aims to identify insight about the patterns of bike usage and the customer base to successfully launch of a similar bike share program in Des Moines, Idaho.

# Results
During the month, bikes were checked out a total of 2,344,224 times. The following visualizatoins exploring this data were generated using Tableau .  


### (1) Checkout Time For Users
![checkout_time_users](https://user-images.githubusercontent.com/106559768/191600649-68fc04c6-426a-495f-982d-96ee0c53adef.png)
A line graph showing the ammount of time bikes each bike rental lasted

### (2) Checkout Times by Gender
![checkout_time_gender](https://user-images.githubusercontent.com/106559768/191601844-731b3ffd-7464-48d9-85dd-abef3b41f0aa.png)
A line graph showing the ammount of time bikes were rented by each gender

### (3) User Trips by Gender
![user_trips_by_gender](https://user-images.githubusercontent.com/106559768/191604330-46d2d6fc-5f8b-4f29-a84b-83ab4c7d88e1.png)

### (4) Trips by Weekday per Hour
![trips_by_weekday_per_hour](https://user-images.githubusercontent.com/106559768/191604732-d67c67fa-41ca-40f9-b32b-b0a59d5de439.png)

## (5) Trips per Weekday by Gender
![trips_by_gender](https://user-images.githubusercontent.com/106559768/191605012-353ae547-5743-4453-baf3-7d22156fb831.png)


# Summary
Overall, the results show that the bike sharing during the month of August in New York City was a popular service. The graph “Checkout Times for Users” [(1)](https://github.com/svujcich/bikesharing/edit/main/README.md#1-checkout-time-for-users) shows on average, people borrowed bikes for less than an hour, with 5 minutes being the most frequent length of trip. The slope of the line following the peak decreases exponentially, meaning that taking shorter rides is a more popular option. Information about trip length can be further broken down to understand the demographics of the riders based on gender. 

The graph ”Checkout Times by Gender” [(2)](https://github.com/svujcich/bikesharing/edit/main/README.md#2-checkout-times-by-gender) shows some similar  information. The curves for both Male and Female users mirror the curve of all users, with take trips that average 5 minutes most frequently, and the curve flattening exponentially following the peak. This graph contains some differences as well.  First, it is apparent that males access bike sharing more than females. Next, regardless of the gender of the user, all users exhibited a similar pattern of trips generally lasting less than 1 hour. This graph also shows some differences. The curve of riders who selected not to share their gender shows a different pattern; unlike the male and female curves, the unknown gender does not appear to have a prominent peak. Instead, it shows more of a plateau that indicates bike rides between 10 and 25 minutes are similar in popularity. Because of the volume of riders who identified their genders, the unknown gender is proportionately small. To explore this demographic, the graph can be filtered to show just riders with unknown genders.  When the graph is filtered, the curve starts to take a familiar shape; and the observation about the popularity of trip lasting between 10 and 25 minutes from the previous graph is confirmed. 

To get a better understanding of the customer base, the graph “User Trips by Gender by Weekday” [(3)](https://github.com/svujcich/bikesharing/edit/main/README.md#3-user-trips-by-gebder) can be analyzed. This graph shows the number of customers and the number of subscribers by the day of the week and gender. The graph indicates male subscribers are utilize bike sharing the most, followed by female subscribers. For both male and female subscribers, weekdays are the most popular days for bike sharing. The information about regular customers tells a different story. For regular customers, the most popular option for gender is to remain anonymous, and the most popular time to ride a bike is on the weekend. There appear to be two separate demographics, regular workweek individuals who use bikes for utility, and weekend riders who use bikes for leisure. Between the subscribers and the customers, one similarity they share is that Wednesdays are the least popular day for bike sharing.

The heatmap “Trips by Weekday per Hour” [(4)](https://github.com/svujcich/bikesharing/edit/main/README.md#4-trips-by-weekday-per-hour)can contribute to a more descriptive picture about daily traffic. At each hour of each day, this map shows how popular was bike sharing was. Like the previous graph, this map indicates lots of biking activity happens on weekdays. Additionally, it specifies in the morning and afternoon when people are going to and returning from work are high traffic times. Like the previous graph, it shows weekend are another popular time to rent bikes, with the most activity happening between 11am- around 5pm. 

This heat map can be broken down again to view the information in the context of the genders. Like the previous graphs, the graph “Trips per Weekday by Gender” [(5)](https://github.com/svujcich/bikesharing/edit/main/README.md#5-trips-per-weekday-by-gender) shows male riders are the biggest customers followed by female sustomers. Similar to the last graph, both male and female riders show peak activity happens on weekdays around the “9 - 5” schedule, and on weekends from the late morning into the late afternoon. The unknown the gender of rider is filtered to show jut the known riders, the highest volume of activity happens on the weekends. This trend also reveals that unknown riders, like the male and female riders, experiences increased traffic between 5pm - 7pm

Another consideration about the customer base is the age demographic. The graph “Age of Riders” shows that the bike sharing is most popular with individuals in their thirties. The graphs also shows people enjoy bike sharing into their seventies which is great news for this startup; biking is for everyone! One thing to note about this graph is it contains an outlier; people with unknown genders overwhelmingly reported they were born in 1969. This piece of information tells us that some people would like to remain completely anonymous.

Over time, bikes will need to be repaired, so bike usage should also be considered. The graph “Bike Utilization” shows all the bike ids by the length of time they have been checked out. The majority of circles share some similarities; most of the bike ids are represented by small, light blue circles, which are a similar size and color. Hovering over the circles to further inspect the data, The rental period for these bikes exist in the same order of magnitude, averaging around 200,000 minutes (around 140 hours) of ride time for the month. This map also has some larger, darker circles. These larger circles that represent bikes the upper end of the bike usage in a month, with trip lengths averaging around 2,000,000 minutes (around 1400 hours).

There are a number of visualizations that could be helpful in understanding this data batter, one which might be useful would include a map of the station locations. By graphing the stations on a map, it wold paint a better picture of the distance between bike stations to begin painting a picture of how to space stations in Des Moines. Another visualization that might be useful would include trip duration by user type to contribute additional insight into pricing subscriptions. 
