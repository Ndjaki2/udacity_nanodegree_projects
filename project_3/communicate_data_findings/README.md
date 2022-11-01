# Ford GoBike Data Exploration
## by Ndjaki Ndjaki


## Dataset

The data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. This dataset can be found [here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv).


## Summary of Findings

In the exploration, I found that the vast majority of people using bikes where men, and that there was a strong relationship between ride duration and days of the week. Actually, bikes were used for more longer at the weekend than they were used on weekdays. I also found that there were two major periods during the day were people started riding; the start and end time were associated with a kind of rush hours, or daytime where people commute to work and come back from.

I also noticed a  surprising result when trying to determine which age group was using the bike sharing system the most. It appeared that it was the Gen Y, more commonly know as Millennials

Outside of the main variables of interest, I verified Customer distribution over Subscriber in terms of ride duration and usage; Customer distribution over the week didn't seem to follow a consistent path, making unpredictable the relationship between it and ride duration. However, there seemed to be an increase on bike demand From Tuesdays to Wednesdays, and from Fridays to Sundays. On another hand, Subscriber seemed to have a steady and evenly distributed ride use over the week. There wasn't really an increase in demand throughout the week.


## Key Insights for Presentation

For the presentation, I focus on the characteristics of bike riding in determining the features that are best for knowing what bikes are mainly used for, when they are used, and the kind of people they are popular with. I leave out some of the features that aren't pertaining to my explanation. I'm to some extent also interested in figuring out how Customer and Subscriber's groups use bike-share system differently.

I believe that start time (meaning riding date and time), member birth year, member gender, and ride duration will be a good guide on determining what rides are mainly used for, when , and by who. I also expect that weekdays and weekends will have the biggest effect figuring out how the bike-sharing system is used differently amongst user types.

Afterwards, I introduce each of the main categorical variables one by one: Gender, Days of week, and User Type. To start, I have a look at the overall gender distribution, followed by the ride demand throughout an entire week, and the type of users riding the bikes. All of these and more are done by plotting the
bike ride distribution amongst Customer and Subscriber's groups; later I analyze how ride start time is spread out throughout the day, along with the users age group, to draw any insights with a couple of histograms.
I use the violin plots to see the relationship between gender and birth year in one way, and duration and weeks of week in another way. In the end, I use a point plot to discover that Subscriber ride duration seems to be steady from Monday to Friday, but there's a light increase in duration on Friday.
