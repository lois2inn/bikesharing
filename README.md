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

Jupyter Notebook is used to convert the trip duration data to datetime type. 
<table>
 <tr>
   <td><img src="images/tripduration_original.png" width="400"/></td>
  <td><img src="images/tripduration_new.png" width="400"/></td>
 </tr>
</table>

#### Visualizations explained

1. With a total of 2,344,224 trips in August 2019, there is much data to visualize. As per the image below, 80% of the users are Subscribers, who make regular use of the bikes and are a predictable source of income for the program. The data also shows that 65% of total bike users are predominantly males followed by females at 25%. 
![User Data](images/usertypes_gender.png "User Types and Gender")

2. The below dashboard shows that the peak hours in August are 7AM-10AM and 4PM-8PM. The bike usage is across all ages, however teenagers and youngsters use more. The bike utilization visual shows the bikes used in the most popular areas. A bike repair plan can be put accordingly.
![NYC Citibike Data](images/report_1.png "NYC Citibike Data")

3. [Checkout Times for all Users](https://public.tableau.com/app/profile/lois2018/viz/Mod14_1_16681998226970/CheckoutTimesforUsers):

4. [Checkout Times by Gender](https://public.tableau.com/app/profile/lois2018/viz/Mod14_2/CheckoutTimesbyGender): 

5. [Trips on Weekday per Hour](https://public.tableau.com/app/profile/lois2018/viz/Mod14_3_16681999413690/TripsByWeekdayperHour):

6. [Trips by Gender on Weekday per Hour](https://public.tableau.com/app/profile/lois2018/viz/Mod14_4/TripsbyGenderWeekdayperHour):

7. [Trips by Gender and User Type](https://public.tableau.com/app/profile/lois2018/viz/Mod14_5/UserTripsbyGender):

8. Number of Rides per Bike:

9. Non-peak hours


## Summary

- high-level summary of the results
 Target bike repairs during nonpeak hours
 Target male population as they will more likely prefer biking shown in August bike trip data.
 Push for subscription
 
 
#### Additional visualizations for future analysis:
- There is a need to understand why the dark colored locations in the below visualization are so popular. Are they close to ferries or subways or workplaces? Understanding the nature of these locations is crucial for establishing bike locations in Des Moines. It would also help to look at how far do bikers travel and which stations are most popular. 
<img src="images/reco_1.png" width="600"/>

- The start and stop locations for bike rides can also be analyzed based on gender. A closer examination of the station locations might provide clarity on why more women aren't using the bike-share program.
<img src="images/reco_2.png" width="600"/>

- The distance covered in a trip can be studied along with duration and subscription costs to get a better picture of why users prefer bikes compared to other transport.

  
