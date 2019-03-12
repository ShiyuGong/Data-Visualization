# Data-Visualization

Designer: Shiyu Gong, Hanli(Helen) Tang

Work Product Name: Merry Christmas, NYC Taxi

Link: https://public.tableau.com/profile/helentang#!/vizhome/finalbackup/Dashboard1?publish=yes 

Data Source: New York City Taxi & Limousine Commission Data

## Executive Summary
This work product is a dashboard illustrating NYC taxi’s whole day on Christmas Day in 2015. It highlights that day’s travel peak hours, travel distances, pick-up locations, and also compares the performance of both yellow and green cab in the city. We choose the data from the New York City Taxi & Limousine Commission website, which contains the yellow and green taxi trips on December 25, 2015. Tableau is the main tool for data visualization.

## Project Goal
The dashboard has two different target audience. The first one is the transportation department of New York City. By looking at history records of Christmas Day’s taxi transportation, the department can have a basic idea of how the traffic will be for the following Christmas Day. The top-left graph shows the traffic peaks and average speed on road. Meanwhile, tourists from other cities also contribute to heavy traffic, which is shown in the “travel from the JFK international airport”. If the transportation department gets good preparation for the situation, they can take quick actions when necessary. In addition, the comparison of yellow and green cab is a good reference for future management.

Another target audience is the traveler. People may probably have various plans for this special holiday. If they have an idea of road traffic conditions, they can prepare for their trips in advance to avoid unnecessary issues. They can get general information of traffic peaks and also the difference between yellow and green cabs. Such information is especially helpful to tourists who are not familiar with the taxi system in NYC. Yellow and green cabs have different operation areas and features. People can choose a more appropriate one based on their needs.

## Data Exploration
Before we explored the data, we had a rough idea of NYC’s traffic and also did a basic research on its taxi system (yellow and green cab). Some results of the data visualization are very useful. For example, the “what time and how long do they travel” graph shows that there are two rush periods, Christmas Eve and Christmas Day afternoon to evening. Only early morning of this day does not have many taxis running on the way. Also, it is clear that most of the rides (around 80%) last less than 15 minutes (900 sec.) demonstrated by the large areas of blue in the chart. Another quite useful information is from the “pick-up location by taxi type”. There is an apparent difference in the pick-up locations of yellow and green cabs. Green cab operates most in Manhattan north and outer boroughs, while yellow cabs operates in anywhere of NYC. In addition, only yellow cab can pick up passengers at JFK. The results are consistent with our research of two cab types.

We also find some insights interesting. Even during the lightest traffic hours on Christmas Day, the max average speed is only 23.64 Mph, which is very slow. It probably represents the traffic problems of NYC. Meanwhile, from the top-right “travel from JFK International Airport”, we can see that most of the rides are long-distance rides to Manhattan area and the traffic is quite heavy from the Christmas afternoon till late night. Another interesting insight is the performance difference of yellow and green cabs. Overall, passengers give higher percentage of tips to yellow cabs than to green cabs, even though green cabs perform longer trip durations.

## Dashboard Design
For the title of the dashboard, we use green and red, two traditional Christmas colors for “MERRY CHRISTMAS” and yellow for “NYC TAXI” and also add a taxi icon to correspond to the topic. We choose to use black as the background color with blue, yellow, and green together as the theme colors. This combination delivers information clearly and provide harmonious visual experience.

The dashboard mainly consists of three parts. The top two parts intend to display the NYC taxi performance on Christmas from an overall perspective. Separated with a horizontal line, the bottom part as a whole compares the difference between two types of taxis, yellow and green, from multiple dimensions. In the whole dashboard, audience can move the mouse over the chart for detailed information of the records would pop up, allowing audience to have enough freedom to look at the parts they are interested in.

The top-left “what time and how long do they travel” is a stacked bar chart which aims to present the rush hours and the distribution of time duration by time. Rides are stacked up as 24 bars based on the time of occurrence and the height of each bar indicates the number of records by hour. The color shows the time duration of each ride. Red indicates longer duration and blue indicates shorter duration. In addition, we also add a line which shows the change of the average speed by time.

The top-right “travel from JFK International Airport” is a destination map which visualizes all the rides beginning from JFK International Airport. Each line represents one ride from origin to destination and the color of the line indicates the trip distance. Red indicates longer trip distance and blue indicates shorter trip distance. What’s more, one interactive element is added to this map which lets audience to observe the change of the rides by time.

The bottom part of the dashboard is a set of visualizations for the comparison between yellow and green taxicabs. To be consistent, we use yellow and green to represent the two types of taxicabs. Firstly, in case the audience are not familiar with the NYC taxi system, we add a brief introduction of the yellow and green taxis on the left of the map. To compare the difference of pick-up locations directly, we utilize the GPS coordinates to make points features to represent all the pick-up locations by taxi type. Besides, the checkbox at the top-right of the map enables audience to compare two pick- up area easily and clearly. Next to the map, a donut chart shows that the cash and credit card are two main payment methods for NYC taxi fare. Beside the donut chart, four pairs of numbers are used to simply demonstrate total distance, total passenger, average total fare and average trip duration. Finally, a line chart is designed to show the tip percentage change by time for two types of taxi. Audience can easily get the knowledge of tip difference.

