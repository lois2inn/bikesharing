# BIKE SHARING

NY Citibike with Tableau

## Overview of the Statistical Analysis

After a trip to NYC and using citibikes there, a data analyst creates a proposal to start a similar bike business in Des Moines. The project focusses on learning how the bike share business works in NYC by reviewing Citibike data in August 2019. The results will then be shared with potential investors in Des Moines. Tableau is used to create visualizations of the below tasks:
- Determine the total trips taken in August 2019.
- Find the proportion of short term customers to annual subscribers.
- Determine the peak usage hours for the month of August.
- Find the top starting and ending locations.
- Determine the gender breakdown of active riders.
- Find the average duration of a bike ride, by age.
- Determine bike utilization and bikes due for repair.
- Determine the length of time that bikes are checked out for all riders and genders.
- Find the number of bike trips for all riders and genders for each hour of each day of the week.
- Find the number of bike trips for each type of user and gender for each day of the week.

## Results

#### Link to Tableau Story

#### Cleaning the data

Jupyter Notebook is used to convert the trip duration data to datetime type. This measure is then used to create subsequent visualizations.
<table>
 <tr>
   <td><img src="images/tripduration_original.png" width="500"/></td>
  <td><img src="images/tripduration_new.png" width="500"/></td>
 </tr>
</table>

#### Visualizations explained

1. With a total of 2,344,224 trips in August 2019, there is much data to visualize.

[!NYC Citibike Data](images/bike_data_overview.png "NYC Citibike Data")

- at least seven visualizations for the NYC Citibike analysis
- a description of the results for each visualization

## Summary

- high-level summary of the results
 Target bike repairs during nonpeak hours
 Target male population as they will more likely prefer biking shown in August bike trip data.
 Push for subscription
 
 
Two additional visualizations are suggested for future analysis
- More insight into why certain starting and ending locations have more number of bikes. 
One reason could be areas of interest (tourism) along Hudson River. Tourism group would be customers instead of subscribers.
- Why do some locations away from the main city center show bike usage? (start locations at north of boroughs) and start/end locations at west of manhattan? could be the proximity to subway and bike to workplace or bike long distance to work. This group would mostly be subscribers.
