# Covid-19 Analysis using R (Tidyverse, ggplot, dplyr)

The New York Times (the Times) has aggregated reported COVID-19 data from state and local governments and health departments since 2020 and provides public access through a repository on GitHub. One of the data sets provided by the Times is county-level data for cumulative cases and deaths each day. This is primary data set for the first two parts of analysis. Additionally, county-level population estimates reported by the US Census Bureau for the years 2010 to 2021 are used as well.

This analysis consists of 3 parts. 

In the first part, following tasks are performed: 
- Calculated the total number of cases and deaths in the United States since March 15, 2020.
- Created a visualization for the total number of deaths and cases in the US since March 15, 2020. 
- Identified the day where the United States had the largest number of new cases and the day where the United States had the largest number of new deaths. 
- Calculated seven-day averages for new cases and deaths per 100,000 people in the United States
- Created a visualization for the seven-day averages for new cases and deaths per 100,000 people in the United States.

While understanding the trends on a national level can be helpful in understanding how COVID-19 impacted the United States, it is important to remember that the virus arrived in the United States at different times. For the next part of your analysis, I looked at COVID related deaths and cases at the state and county-levels. 

Building of the work from Part 1, I completed the following sections: 
- Determined the top 10 states in terms of total deaths and cases between March 15, 2020, and December 31, 2021. 
- Determined the top 10 states in terms of deaths and cases per 100,000 people between March 15, 2020, and December 31, 2021. 
- Then, selected a state and: 
    - Calculated seven-day averages for new cases and deaths per 100,000 people in the state.
    - Created a visualization comparing the seven-day averages per 100,000 people in the state to the seven-day averages per 100,000 people for the entire United States.
    - Identified the top 5 counties in the state in terms of deaths and cases per 100,000 people.
    - Created a visualization to map the deaths per 100,000 people in each county in the state. 
- Finally, selected three other states and: 
    - Calculated the number of deaths and cases per 100,000 people for each state each day between March 15, 2020, and December 31, 2021. 
    - Created a visualization to compare the number of deaths and cases per 100,000 people for each state by date.
    
Finally, for the third part of the analysis, I investigated the impact of COVID-19 on a global scale. The NY Times data does not contain data reported outside the US. Consequently, I used another public access repository from the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University. To get started, I first verified that the data in both reporting bodies were similar.

For the last part of my analysis, I performed following tasks:
- Identified the top 10 countries with the most confirmed cases per 100,000 people. 
- Identified the top 10 countries with the most confirmed deaths per 100,000 people. 
- Constructed a visualization for the number of confirmed cases versus time for the top 10 countries.
- Then, selected four countries on one of the continents and: 
    - Constructed a visualization for the number of confirmed cases per 100,000 people verses time 
    - Constructed a visualization for the number of deaths per 100,000 people verses time
