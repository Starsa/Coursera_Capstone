# Coursera Capstone
Final Capstone from IBM Data Science Coursera

## Battle of the Neighborhoods 
***Toronto vs. New York***
 
### Table of contents
-  Introduction
-  Data
-  Methodology
-  Analysis
-  Results
-  Conclusion
 
 
 
### Introduction: 
New York City and Toronto are considered financial capitals of their respective countries, USA and Canada. Both cities are located on the east coast of North America. Toronto has a population of 2.7 million people while New York 8.2 million. Both cities are considered the most populous respectively.
In this project we will look at neighborhood and venue data to conduct a comparison of both cities which may garner some insight as to what each city has to offer, and how they compare to one another.
 
 
### Data:
We will be using the FourSquare api to give us location and venue data along with additional data for each city. The Toronto data for postal codes and neighborhoods was obtained from wikipedia pages of postal codes of Canada here.
New York has a total of 5 boroughs and 306 neighborhoods. Data was available here as part of the coursera course from IBM in Data Science.
 
 
### Methodology
Data was preprocessed to produce dataframes of each city's neighborhoods with corresponding top 10 venues in that neighborhood. K means cluster analysis was then done for both cities individually and finally on the combined dataset of both cities. We have used visuals including distribution plots and barplots for comparison as well as maps demonstrating clustering of venues. 


### Analysis:
We were able to do a direct comparison and clustering analysis of both cities. Finally we compared both cluster dataframes to get our direct comparison


### Results:
In this study we investigated neighborhoods of Toronto and New York. We used k means clustering method to make sense of the data. The majority of the neighborhoods seem to fall into busy district type of neighborhoods. There is also clearly more parks in Toronto than in NY. Also it seems that there are beaches in NY and not in Toronto. That could be because its colder in Toronto compared to New York.

### Conclusion:
There are a lot of similarities between the two cities, Toronto & New York, especially topigraphically with incredibly similar clustering patterns!
