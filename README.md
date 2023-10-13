# Tableau
This project is part of Module 18 Challenge of the Monash University Data Analytics Bootcamp. 

## Project Description
### Problem
Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data on the program's utilisation. Each month, bike data is collected, organised, and made public on the Citi Bike DataLinks to an external site. webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have questions about the program, so your first task on the job is to build a set of data reports to provide the answers.

### Deliverables
1. Design 2–5 visualisations for each discovered phenomenon (4–10 total).
2. Use your visualisations (not necessarily all of them) to design a dashboard for each phenomenon. The dashboards should be accompanied by an analysis explaining why the phenomenon may be occurring.
3. Create a static or dynamic map that plots all bike stations.
4. Create your final presentation in Tableau in the form of dashboards and stories. 

### Link to My Tableau Public Workbook 
https://public.tableau.com/views/Module18_Challenge_16966412707470/Map_StartStationPopularity?:language=en-GB&publish=yes&:display_count=n&:origin=viz_share_link

**Please view visualisations and dashboards in full screen.**

## Analysis 

The following analysis is about citibike data that was collected from May to July in 2023 in Jersey City. The data does inlude some bike stations located in New York City due to bike journeys crossing the Hudson River and ending the journey in New York City. 

### Dashboards & Maps
The first dashboard, Starting the Journey, displays information about starting the bike journey in Jersey City. Just under 300, 000 trips were taken between May and July and the average distance travelled was 0.73 miles. 
The top 10 bike stations to begin a journey are located in suburbs along the length of the Hudson river with zip codes 07302, 07310 and 07030. All of these stations except two have a higher usage by members. '12 St and Sinatra Dr' and 'South Waterfront Walkway' are predominantly used by casual users. According to unitedstateszipcodes.org, the demographic of these zicodes are people aged in their late 20s to early 40s while an extremely small number are middle aged adults. These is also an extremely large number of single adults and small number of familes. The median household income in these three suburbs is between $98000 and $133000 USD.
The least popular stations are located in suburbs 07304, 07306, 07307, 07087 and 07310. Each of these stations have a count of 1 trip. The age of the people living in these zipcodes is the same as the those living in zipcodes of the top 10 stations. The main noticeable difference (except for zipcode 07310) is the median household income, being between $40000 - $480000 USD. 
The most popular time the bikes are used during the day is first at 8 am and in the late afternoon at 6 pm. This trend is true for each month from from May to July.

The second dashboard takes a closer look at the type of users that use citibikes in Jersey City. Approximately 71% of users are members and the rest are casual users. Interesting trends are noticed with the spidermap that shows distance of trip by type of user. When the day slider is adjusted for the month of May, two things can be noticed. Members is Jersey City cross the river to New York City more as the month progresses, for instance there are more river crossings in the middle of the month comapred to the beginning. Also, casual users do cross the river but these trips are considerably less compared with trips taken by members.

In addition, with regards to the number trips taken members and casual users per month, the month of July had the highest casual user numbers at approximatey 1700. May had the lowest trips by casual users at 345 trips. The highest number of trips taken by members was in May at 2731 trips. May also had the lowest number of trips taken by a member at 845 trips. June had low drops in trip numbers taken by members, the lowest number of trips being 1765 trips.
### Other Visualisations 

