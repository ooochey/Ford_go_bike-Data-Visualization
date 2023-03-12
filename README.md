# (Dataset Exploration Title)
## by (Nwayalani Uche)


## Dataset

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. There are about 161452 individual rides in the dataset after wrangling with 18 features such as duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude, end_station_longitude, bike_id, user_type, member_birth_year, member_gender, bike_share_for_all_trip, distance and age most of which were numerical, there were however some categorical data such as user_type, member_gender and bike_share_for_all_trip.


## Summary of Findings

> Exploration shows positive relationship between duration it takes for a ride from start point  to finish point and the the distance covered in the ride as each of the variables were tranformed to a logarithm scale, further exploration was done to assess the relationship between duration of ride and other variables such as Age, Gender and User type which reavealed that there was no significant relationship with Age and the female gender tends use to more average time to cover each ride compared to other or male while the customers also spend more time averagely on a ride that the subcribers.

> Outside the main variable of interest, I tried to confirm the relationship between distance covered and other features since there was a positive correlation between duration and distance covered. The relationship between distance covered and user type was similar to what was obtained with duration however it was a bit different with gender where the other gender tend to cover more distance averagely when compared with Female that relatively also maintained a high distance covered and male gender that covered the least distance. furthermore, i tried to establish whether or not the high average duration of ride among the female gender was due to the higher distance covered and it showed that the higher duration in female may be due to higher average distance covered 

## Key Insights for Presentation

> For the presentation, I focused on the influence other features such as distance covered, age of rider and categrical variables such as Gender and user type have on the duration it take to complete a ride. I started by plotting a standard distribution of the main feature of interest (duration of ride) and other features such as distance covered, Age, Gender and User type. Using Histogram for the numeric variables  such as duration of ride, distance covered and age which were subsequently followed a log scaled tranformation where necessary while bar charts were used for the categorical variables.

> The relationship between all the numeric variables of interests were assessed using correlation marix heatmap and scatter plot followed by the distribution of duration of ride based on some of the categorical variable such as Gender and user type using boxplot.

> Finally, a multivariate scatter plot of duration of ride against distance covered was done based on the different gender using color pallete to distinguish between each gender followed by a faceted multivariate scattered plot of duration of ride and distance covered based on the two categorical variables being assessed, Gender and User type.