# Bike Sharing in NYC

For this project, we reviewed bike sharing data from the Citi Bikes program in New York City. This was studied with the intent applying this program to Des Moines Iowa, so any key trends from the New York data would greatly inform efforts for subsequent expansions. 

[Data & Analysis Can Be Found Here](https://public.tableau.com/profile/carlos.jennings#!/vizhome/BikeSharingProject/Story1)

---
## Resources
- [x] Python (jupyter notebook)
- [x] Tableau

---

### Results 1: Starting Location

<img src="https://github.com/carlosjennings1991/bikesharing/blob/main/Starting_Location.png">

In the map above, we can see that most bike starts occur in the dense, tourist & commercial centers of Manhattan, so Central Park-South all the way down to Wall Street. 

<br>

---

### Results 2: Ending Locations

<img src="https://github.com/carlosjennings1991/bikesharing/blob/main/Ending_Locations.png">

Similar to the previous map, but showing ending locations. These closely mirror start locations albeit with minute differences, however the overall pattern is clearly the same. 

<br>

---

### Results 3: Checkout Times for Each Bike

<img src="https://github.com/carlosjennings1991/bikesharing/blob/main/Rides_By_Duration.png">

Based on the above, we can see that the overwhelming majority of bike trips were short in duration i.e less than 20 minutes. 

<br>

---

### Results 4: Checkout Times for Each Bike, by Gender

<img src="https://github.com/carlosjennings1991/bikesharing/blob/main/Rides_by_Bike_by_Gender.png">

Each of the three tracked genders (Male, Female, Unknown) broadly show similar patterns. Most trips are still short in duration, however, Female and Unknown bikers ride durations slow more slowly relative to Male bike rides. 

<br>

---

### Results 5: Bike Trips per day, per hour.

<img src="https://github.com/carlosjennings1991/bikesharing/blob/main/Bike_trips_per_day_per_hour.png">

The amount of bike rides per day show two general trends. First and foremost, bike rides during weekdays closely parallel rush hour commute times i.e morning and mid-afternoon. Conversely, the weekend there are no morning and afternoon spikes, but rather slowly increase towards noon-2pm. 

There is one curious outlier - Wednesday afternoon. For some reason afternoon rides on Wednesday are much fewer relative to other weekday afternoons. 

<br>

---

### Results 6: Bike Trips per day, per hour, per Gender.

<img src="https://github.com/carlosjennings1991/bikesharing/blob/main/ride_times_by_gender.png">

This chart shows the above chart, but broken down by gender. A few patterns emerge. Female and Male ride patterns resemble each other, with the male pattern being starker simply as a result of there being more men bike riders. However, those of unknown gender present a different pattern, with slightly more rides ocurring during the weekend vs. weekdays.

<br>

---

### Results 7: User Trips per day, per Gender

<img src="https://github.com/carlosjennings1991/bikesharing/blob/main/trips_by_gender_by_user_type.png">

Here we see the breakdown of rides, by gender but further differentiated by user type i.e subscriber or non-subscriber. 
We can see than subscribers are much more likely to be men. Women have a moderate amount of subscribers and those of Unknown gender show very few subscribers.

---

### Summary

Based on our analysis of New York's data, a few key takeaways emerge. 

1. Men are much more likely to be subscribers (and therefore generate consistent and predictable revenue). 
2. Commercial and Tourist centers are by far the most popular ending and start destinations. The primarily residential areas of NYC - upper Manhattan and the outer Boroughs show much less activity. 

For the purposes of Des Moines Iowa, this means concentrating stations downtown, along the river, the State Capitol (east of Downtown) and Drake University. 

Of course, New York City and Des Moines are very different cities. While some trends are likely to transfer, others may surprise us. For instance, how many of the bike riders were tourists? How many of them were students? What was the average distance of the bike ride? If we had data on those three variables, we could more precisely alter the Des Moines expansion to fit Des Moines' built environment. 
