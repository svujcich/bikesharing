# Overview
Bike sharing is a trend in which individuals rent and use bicycles for a fee.  In this project, Tableau was used to generate visualizations to analyze data from a bikeshare in New York City during the month of August. By exploring bike usage trends in relation to user demographics, this project aims to identify insight about the patterns of bike usage and the customer base to successfully launch of a similar bike share program in Des Moines, Iowa. the following images can be explored on on Tableau Public [here](https://public.tableau.com/app/profile/sarah.vujcich/viz/TableauChallenge_16636310165940/BikeUsageinNYC).

# Results

### (1) Checkout Time For Users
![checkout_time_users](https://user-images.githubusercontent.com/106559768/191600649-68fc04c6-426a-495f-982d-96ee0c53adef.png)
A line graph showing the ammount of time each bike rental lasted

### (2) Checkout Times by Gender
![checkout_time_gender](https://user-images.githubusercontent.com/106559768/191601844-731b3ffd-7464-48d9-85dd-abef3b41f0aa.png)
A line graph showing the ammount of time bikes were rented by each gender

### (3) User Trips by Gender by Weekday
![user_trips_by_gender](https://user-images.githubusercontent.com/106559768/191638630-599e7d1c-e9ba-4a91-a2ff-8b02e0db41a1.png)

A heatmap which shows different user typer (customers vs. subscribers) by gender and day of the week.

### (4) Trips per Weekday per Hour
![trips_per_weekday_per_hour](https://user-images.githubusercontent.com/106559768/191665020-a7c44452-8728-4415-9171-1b1bf0f29e84.png)


A heatmap which shows the breakdown of user activity for each day of the week by hour. 

### (5) Trips per Weekday per Hour by Gender
![trips_per_weekday_per_hour_by_gender](https://user-images.githubusercontent.com/106559768/191665271-1e36c00c-8ca6-4d8d-a367-a4b4ed834569.png)


A series of heat maps which show the breakdown of user activity for each day of the week by gender

### (6) Age of Riders
![age_of_riders](https://user-images.githubusercontent.com/106559768/191637677-de281c5a-b51c-41c1-9385-427d71b45a7c.png)
A series of graphs which show the age dempgraphic of riders by gender

### (7) Frequency of Bike Utilization
![frequency_of_bike_utilization](https://user-images.githubusercontent.com/106559768/191642038-b63af61b-d80a-45b9-83ac-ff0b838fe9d0.png)
requency of Bike Utilization
A heatmap which shows how frequently each bike is bing used based on size and color of the square 

# Summary
Overall, the results show that the bike sharing during the month of August in New York City was a popular service. The graph “Checkout Times for Users” [(1)](https://github.com/svujcich/bikesharing/edit/main/README.md#1-checkout-time-for-users) shows on average, people borrowed bikes for less than an hour, with 5 minutes being the most frequent length of trip. The slope of the line following the peak decreases exponentially, meaning that taking shorter rides is a more popular option. Information about trip length can be further broken down to understand the demographics of the riders based on gender. 

The graph ”Checkout Times by Gender” [(2)](https://github.com/svujcich/bikesharing/edit/main/README.md#2-checkout-times-by-gender) shows some similar  information. The curves for both Male and Female users mirror the curve of all users, with take trips that average 5 minutes most frequently, and the curve flattening exponentially following the peak. This graph contains some differences as well.  First, it is apparent that males access bike sharing more than females. Next, regardless of the gender of the user, all users exhibited a similar pattern of trips generally lasting less than 1 hour. This graph also shows some differences. The curve of riders who selected not to share their gender shows a different pattern; unlike the male and female curves, the unknown gender does not appear to have a prominent peak. Instead, it shows more of a plateau that indicates bike rides between 10 and 25 minutes are similar in popularity. Because of the volume of riders who identified their genders, the unknown gender is proportionately small. To explore this demographic, the graph can be filtered to show just riders with unknown genders.  
![checkout_time_gender_unknown](https://user-images.githubusercontent.com/106559768/191658127-fc06dbb8-6a2a-415e-afaa-8f2155ed6f18.png)
When the graph is filtered, the curve starts to take a familiar shape; and the observation about the popularity of trip lasting between 10 and 25 minutes from the previous graph is confirmed. 

To get a better understanding of the customer base, the graph “User Trips by Gender by Weekday” [(3)](https://github.com/svujcich/bikesharing/edit/main/README.md#3-user-trips-by-gender-by-weekday) can be analyzed. This graph shows the number of customers and the number of subscribers by the day of the week and gender. The graph indicates male subscribers are utilize bike sharing the most, followed by female subscribers. For both male and female subscribers, weekdays are the most popular days for bike sharing. The information about regular customers tells a different story. When the results are filtered to show users with unknown genders, the most popular option for gender is to remain anonymous, and the most popular time to ride a bike is on the weekend. 

![customer_usage](https://user-images.githubusercontent.com/106559768/191663098-a2b90e0e-f40c-44fb-9e7d-44c696a634de.png)

Using heat maps to visualize the breakdown of traffic by hour for each day the analysis shows that the bikesharing service is popular among two separate demographics; regular workweek individuals who use bikes for utility, and weekend riders who use bikes for leisure. Between the subscribers and the customers, one similarity they share is that Wednesdays are the least popular day for bike sharing.

The heatmap “Trips per Weekday per Hour” [(4)](https://github.com/svujcich/bikesharing/edit/main/README.md#4-trips-per-weekday-per-hour) can contribute to a more descriptive picture about daily traffic. At each hour of each day, this map shows how popular was bike sharing was. This map echoes a lot of information that has already been explored. This heatmap shows lots of biking activity happens on weekdays. Additionally, it specifies in the morning and afternoon when people are going to and returning from work are high traffic times. This map shows weekend are another popular time to rent bikes, and additionally specifies the most activity happens between 11am - around 5pm. 

This heat map can be broken down again to view the information in the context of the genders. Like the previous graphs, the graph “Trips per Weekday per Hour by Gender” [(5)](https://github.com/svujcich/bikesharing/edit/main/README.md#5-trips-per-weekday-per-hour-by-gender) shows male riders are the biggest customers followed by female sustomers. Similar to the last graph, both male and female riders show peak activity happens on weekdays around the “9 - 5” schedule, and on weekends from the late morning into the late afternoon. The unknown the gender of rider is filtered to show jut the known riders, the highest volume of activity happens on the weekends. This trend also reveals that unknown riders, like the male and female riders, experiences increased traffic between 5pm - 7pm

Another consideration about the customer base is the age demographic. The graph “Age of Riders” [(6)](https://github.com/svujcich/bikesharing/edit/main/README.md#6-age-of-riders) shows that the bike sharing is most popular with individuals in their thirties. The graphs also shows people enjoy bike sharing into their seventies which is great news for this startup; biking is for everyone! One thing to note about this graph is it contains an outlier; people with unknown genders overwhelmingly reported they were born in 1969. This piece of information tells us that most people who would prefer nt to disclose their gender also prefer to  remain completely anonymous.

Over time, bikes will need to be repaired, so bike usage should also be considered. The graph “Frequency of Bike Utilization" [(7)](https://github.com/svujcich/bikesharing/edit/main/README.md#7-frequency-of-bike-utilization) shows all the bike ids by the number of time they have been checked out. Bikes that are utilized more are represented by bigger, darker squares. This graph is useful because by hovering over any given suare in tableau, the bike number will prompt a pupup with the bike number, making it easier to see which bikes might need to be rotated around or inspected.

A number of other visualizations that could be helpful in understanding this data better. One visualization which might be useful would be a map of the station locations. Graphing the stations on a map  would paint a better picture of how bike stations are distanced from eachother, and begin to answer the question "where should stations be located". Another visualization that might be useful would age of riders by user type. This graph might begin to draw a picture about who how to best market to various target audiences.

Understanding the scope of the service as well as the target audience is a great start to building a bikeshare enterprise. With a little additional location-specific research, Des Moines will be on its way to sustainable transportation program in no time.

** Note that due to size constraints of github, original data files were not uploaded to repository. 
