# Incubator_Proposal
# Exploring the Network of Popular American Hip-hop Artists
*Bobae Kang*  
*07-24-2017*  

## Summary

This currently repository stores the preliminary work of my project for the Data Incubator Fellowship Program. In this project, I seek to gain an insight into the network of popular U.S. rappers, whose songs have been ranked on Billboard's weekly Hot Rap Songs list. The main motivation comes from my recent interest in American hip-hop and rap artists. By exploring and examining the featuring network of rappers, I seek to present how popular rappers are connected to each other by the means of collaborating on their creative works as well as how such connections have changed over time. When completed, this project will offer insights into a major component of the current American pop culture, i.e., hip-hop and rap, including its key players and their collaborative efforts and historical trends. Furthermore, the project can be readily generalized beyond hip-hop and rap to encompass other genres of music.


## Data

The current project uses data from [Billboard's weekly chart of Hot Rap Songs](www.billboard.com/charts/rap-song). Every week, Billboard selects and presents the most popular current rap songs of the week, ranked from 1 to 25. According to the official explanation, these songs are ranked by:

> radio airplay audience impressions as measured by Nielsen Music, sales data as compiled by Nielsen Music SoundScan and streaming activity data from online music sources tracked by Nielsen Music. Songs are defined as current if they are newly-released titles, or songs receiving widespread airplay and/or sales activity for the first time.

Using the data scrapped from Billboard's Hot Rap Songs weekly chart webpages, the current project aims to provide information on on how various artists are related to one another via collaboration. The project will use 10 years of weekly charts for analysis, examining the network of over 500 artists embodied in 13,000 tracks (with repeats).


## Methodology

Central to the current project is a simple network analysis, which compares 10 annually formed networks of artists for 10 years. Each network is represnted by a directed graph, where each node is an artist and each edge marks a collaboration between artists linked by the edge. Each edge originates from a featuring artist and reaches to an artist who wrote the song.


## Planned outcome

The culmination of the current project will be an app that enables users to see the evolving network of popular hip-hop and rap artists interactively. Users will be able to select and change the calender year to make comparisons across the yearly networks and click on a specific artist to find more about the artist as well as the artist's creative/collaborative connections. The app will also provide information on how the artists are connected to one another, how fruitful the connections are (measured by the number of collaborative works on the weekly chart from the given year as well as over time), and more! 


## Preliminary explorations

The following two plots hint at what is to come for the current project.

![network_graph](/images/network_graph.png)

The first plot is a directional graph illustrating a sample network of hip-hop artists based on the Billboard Hot Rap Songs chart over the last quarter (13 weeks). In the middel of the plot are artists with a high number of featurings. We observe that these artists are roughly equivalent to those who are currently the best known and most influential.

![featuring_barh](/images/featuring_barh.png)

The second plot is a horizontal bar graph illustrating the distribution of the number of featurings among artists over the last 10 years (52*10 weeks). We find that this is a highly skewed distribution since more than 500 artists appeared on the Hot Rap Songs chart over the last year. We also observe that those with a high number of featurings are mostly well-known artists.# Incubator_Proposal
