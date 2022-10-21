# (Ford GoBike System Data Exploration)
## by (Jude Nyamekye Koomson)


## Dataset
The dataset includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. 
There are 183412 entries in the dataset with 16 features(columns) namley:(duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude, end_station_longitude, bike_id, user_type, member_birth_year, member_gender, bike_share_for_all_trip)
There were missing data in the dataset : start_station_id - 197, start_station_name - 197, end_station_id - 197, end_station_name - 197, member_birth_year - 8265, member_gender - 8265


## Summary of Findings

From the exploratory analysis, we find that the users (type of users) of Ford GoBike System are mainly customers and subscribers. Again, from the bar graph plot, Subscriber user_type recored the highest frequency count, followed by Customer user_type. Figuratively, Subscriber user_type and Customer user_type recorded 163,544 counts and 19,868 counts respectively.
It was also observed that age 31 is identified as the age with highest count among users, followed by ages 26, 30, 29, 28, to mention but a few respectively.

Again, from our findings, Yes means there was sharing of bike for all trip and No means there was not sharing of same bike for some trips. Figuratively, No bike sharing recorded 157606 counts and Yes also recorded 17346 counts
We observed that the gender of Ford Bike System are mainly:
    Male - 130500 counts, Female - 40805, Other - 3647
    

From the graph, it can be observed that "Male" gender was the highest among both the Subscriber user type and Customer user type, followed by "Female" gender in both user types. Last but not the least, "Other Genders" placed third place among both user types

The relationship between Female gender and other gender reagdiing sharing of bike for all trip, it was found that no-bike-sharing was predominately more among Male gender, female gender and Other gender respectively.
One of the relationships observed was the relationship between Female gender and other gender was the sharing of bike for all trip. However, no-bike-sharing was predominately among Male gender, female gender and Other gender respectively.In terms of population, the male gender recorded the highest counts across all other variable distribution, followed by female gender and other genders respectively.

Additionally, we further proved that it is possible that either older members of ages 100 and above are fewer when it comes to reaching their ride end station or fewer older people actually patronise Ford GoBike System. 

From the plot, it was observed that both customer and subscriber user types of age less than 80 years were associated with high count of bike ride duration


## Key Insights for Presentation

For the presentation, I focus on just the influence of the user_types, member_gender, and age_of_member of the datasets.
I start by introducing the user types, followed by the pattern in gender, then plot the histplot.

Afterwards, I introduce each of the member gender one by one. To start, I use the bar plots of user_type and age of member. I'm only looking at the user tye plot here since it's the clearest example of how the categorical gender of member affect number of users.I've made sure to use different color palettes for each quality variable to make sure it is clear that they're different between plots.
