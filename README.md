# New York City resident complainst
*Season Yang*  
*07-24-2017*  

## Summary

The history of New York City can be traced by to 1624 when colonists of the Dutch Republic set the Lower Manhattan as a trading harbor.  Today, with the estimated of population of 8,537,673, New York has become the most populous city in the United States.  As a graduate student from Columbia University, I feel honored studying in one of the greatest city in the world.  

However, as a city that has over 300 years of history, New York City exists many issues and thus for the Data Incubator Fellowship, I am proposing a project to raise awareness of New York City problems.  To solve problems, we must first recognize what are the problems and which are the most severe ones.  Therefore, my primary project data will be the New York City 311 Service Requests data.  Through residential complaints, I intend to recognize and analyze New York City major issues and determine if New York authorities made the efforts to solve those problems.


## Data

The New York City 311 Service Requests data contains all the service requests (or complaints) from 2011 to present and it is 10G dataset.  The important attributes of this dataset include time, locations of complaints, responsible agencies, descriptions (solved or not), types of complaints and cities.  For my preliminary analysis, I used the 2015 data.

## Approach -- Part 1
My proposed project has twofold objective.  The first is to recognize severe problems.  Using data science tool (such as decision tree), I will look for severe problem-types and analyze what are the main factors that contribute to those problems (such as locations and time).  For example, in my first figure, I used bar plot to count the most frequent complaint types of the major cities in New York area. Through this figure, I have found some interesting observations.  Even though Manhattan has the densest population, within the most common complaints, Brooklyn and Bronx share larger complaint proportion.  For the complaint type, Blocked Driveway, the complaints for Brooklyn and Bronx exceed Manhattan by large amount.  In the future, I will focus on the description column and use nature language processing skill to determine if the issues are solved.  In the meantime, I will use all the dataset from 2011 to present and check how the same issues progress through time.

![network_graph](/images/Most_Comp_City.png)


## Approach -- Part 2

The second object is to analyze if New York authorities made the efforts to solve those problems by specifically focusing on New York traffic.  Using the residential complaints and combining with NYPD Motor Vehicles Collision data (includes the data of collusion such as location and time), I intend to analyze if the 311 service request lower the rate of collision progressing through time.  For example, in my second figure, I plotted out the 2015 complaints on traffic and street light, along with all the rush hour collisions happened in 2015.  By observation, it showed us the correlation between residential complaints on traffic and collision. 

!(/images/Collision_and_Traffic_Complaint.png)
