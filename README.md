
# BikeSharing 
## Overview 
Using Tablea by using data from NYC Bike Share provided in a csv file for the month of August I performed data engineering on the data to show our stakeholders/investors reasons why a Bike Share company would be great for Des Moines, Iowa. I began my data engineering on the csv file and changed the datatype of a column in order to create time series graphs in Tableau In addition I created visualizations that show the differences bike checkout times for the type of user and gender throughout the day as a heatmap. I then created a story in Tableau and wrote a report describing the key outcomes of the NYC analysis.
    
![tripcolumn_datetime_datatype](https://user-images.githubusercontent.com/94208810/154889485-6d08a8a0-b240-4910-8ab0-5a8016820471.png)


## Results
Visualizations providing a summary of each visualization inside my Tableau story.
1. Length time bikes are checked out for users. 
Can filter on trip duration by the hour.

![checkout time for users](https://user-images.githubusercontent.com/94208810/154889345-8e268623-773d-4d29-95f6-567f37967053.png)

2. Length of time that bikes are checked out for each gender. 
Can filter on Trip duration by hour and shows legend for Gender and is represented by color in line graph. 

![checkout times by gender](https://user-images.githubusercontent.com/94208810/154889376-54b67193-521c-4d47-927b-8eed040a36dd.png)


3. Trips By Weekday for Each Hour
Graph of the number of bike trips by weekday for each hour of the day as a heatmap.

![Total Bike Trips By Weekday for Each Hour](https://user-images.githubusercontent.com/94208810/154889407-4e71c4fc-430a-4383-aab4-94f37739f60e.png)


4. Trips by Gender (Weekday per Hour)
Graph of the number of bike trips by gender for each hour of each day of the week as a heatmap.
![Total Bike Trips By Gender (Weekday per Hour)](https://user-images.githubusercontent.com/94208810/154889426-af03943c-25ea-4b07-be08-ed6f3f2bc78b.png)

5. User Trips by Gender by Weekday
Heatmap that shows the number of bike trips broken down by gender for each day of the week by each User Type.
![Bike Trips by Gender (weekday per Hour)](https://user-images.githubusercontent.com/94208810/154889464-4895c640-6e8a-45be-8524-a7964ef01ae1.png)


6. Top Ten or Most Popular Starting Locations for Bike RntTrips
   Scatter Map highlighting with Markers by User type the most populart start locations stations for bike trip. 
   
![Popular Bike Trip Start Location](https://user-images.githubusercontent.com/94208810/154895646-bdb275fc-40fa-4efa-8174-ff9f3ebc0dce.png)


7. Top Ten or Most Popular Ending Locations for Bike Trips
   Scatter Map highlighting with Markers by User type the most populart start locations stations for bike trip. 

![Most Popular Bike Trip ENd Locations](https://user-images.githubusercontent.com/94208810/154895690-c75f0ca9-79f0-447e-9106-5e79a3928227.png)

## Summary
This shows the most popular duration for bike trips and also shows which hour is most popular during the day for each weekday. The length of time the most bikes were checked out were for 5 minute trip duration and were by subscriber and were of male gender. The most popular lenght of bike rides were between 0 and 59 seconds with Subscriber Males. 
There is a ine graph displaying the number of bikes that are checked out by duration for each gender by the hour, and the graph can get filtered by the hour and gender. The most bikes were checked out on Thursday by Males between 5:00 and  6:00 P.M. and also saw that 5 and 6:00 P.M. were popular times on Monday Wednesday and Thursday. 
A heatmap is created showing the number of bike trips for each hour of each day of the week. This showed the most popular day of the week with highest amount of bike rides were on Thursdays and were by Male Gender. The Total number of bike rides were of 44,886 rides. 
A heatmap is created showing the number  of bike trips by gener for each hour of each day of the week and the heat map can be filtered by gender This map showed to that thursday were most popular time of day for males and the most popular hour was between 5-6 p.m. 
A heatmap is created showing the number of bie trips for each type of user and gender for each day of the week and you can only filter by user and gender. 
A Scatter Map of the Ten most popular bike ride start and end locations. The most popular location for both were in Manahattan. 
Most popular time of the week for Male Subscribers were Thursday, Friday and Saturdays with highest amout of bike trips and Same was true for Female Subscribers with most popular bike trips. The Cusomters most popular time for bike trips was on Saturday and were unknowns genders.   
