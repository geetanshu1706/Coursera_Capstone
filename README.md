# Coursera_Capstone - NYC Battle of neighborhoods
## Busniess Problem
New York is one of the worst hit state by COVID-19 in USA. New York city was at the center of the disaster. The hospitals are already stretched thin with patients overflowing. According to [New York Times report](https://www.nytimes.com/interactive/2020/nyregion/new-york-city-coronavirus-cases.html), (at the moment of writing) death toll was 22795, case count topped 223,9677.

I was motivated by this to create something useful which would give some insight on this situation. In this project we are going to determine which neighborhood is best prepared for this pandemic, by finding out the best ratio of hospital beds per person for each neighborhood in this city.

*The report here should not be used as a measuring tool, because the situation has been changed a lot since Coronavirus COVID-19 has hit the city. And keeps changing day by day as some states are opening and some are closing back again. This report is intended to help people who are planning to move to New York during or after this pandemic to start their new lives ( school or jobs).* 


## Data
Data
Data will be collected data from following sources:
1.	New York City data that contains borough, neighborhoods along with their latitudes and longitudes.
  o	Data source: [NYC data set](https://cocl.us/new_york_dataset).
2.	We are going to get population data from Scraping Wikipedia.
  o	Data source: [Wikipedia page of NYC neighborhood](https://en.wikipedia.org/wiki/Neighborhoods_in_New_York_City).
o	We are going to go through each of the links of neighborhood and find the population of each of them.
3.	Hospital information is going to be fetched from foursquare API.
  o	Data source: foursquare API
4.	Hospital bed information is going to be fetched from NYS Health Profile website.
  o	Data source: [NYS Health Profile](https://en.wikipedia.org/wiki/Neighborhoods_in_New_York_City).
  
## Approach
  Approach to resolve issue:
•	Collect the[ New York city dataset](https://cocl.us/new_york_dataset).
•	Collect population data for each neighborhood by scraping Wikipedia.
•	Using Foursquare API we will get hospitals for each neighborhood.
•	Collect hospital bed data by scraping data from NYS Health Profile.
•	Data Visualization and some statistical analysis.
•	Analyzing using Clustering (Specially K-Means).
•	Find the best value of K
•	Visualize the neighborhood max density of hospital beds per 100 people.
•	Visualize the neighborhood max density of hospital ICU beds per 100 people.
•	Inference From these results and related conclusions.


## Data preparation
Data used in the analysis are listed below:

•	First, collect the json dataset, which will contain borough, neighborhood, latitude and longitude information.
•	Neighborhood data in New York City will be collected from scraping the Wikipedia page.
•links given in the neighborhood section of the table will be visited via scraper, and find the population for each of them. Then data will be cleaned up and used to create a      data frame containing borough, neighborhood and population.
•	Hospitals per neighborhood information will be collected from foursquare API.
•	We will collect bed and ICU capacity information from NYS Health Profile website. 



