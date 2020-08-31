# (Dataset Exploration Title)
## Nouf Alotaibi


## Dataset

> The dataset consist of approximately 1,85M bike trips from FY2018. The features include the trip duration, start/end time, start/end station, Bike id, User type and Bike share for all trips. The data can be found <a> href="https://www.lyft.com/bikes/bay-wheels/system-data">Here</a>

## Summary of Findings

> - The majority of the bike trips take approximately 600 seconds.
> - The Ford GoBike system is used mostly in October, July, and June.
> - The duration of the trips was consistent at the beginning of the year. June and July had the longest trips, while November and December had the shortest trips.
> - Ford GoBike system has more subscribers (85%) than non-subscribers (15%).
> - October is the most frequent month for the subscriber, while For the customer, it is July.
> - The customer has a lot of long trips in duration compared to the subscriber.


## Key Insights for Presentation

> In Presentation, I focused on the bay Area bike share system users and their behavior, the average trip duration, and the Monthly usage of the system, starting by introducing the distribution of the system users. Afterward, I used pointplot to show the average trip of durations per month. To finish, I introduced monthly usage of the system per user type to show that both subscribers and customers ride the most during the summertime and less during winter. 

jupyter nbconvert slide_deck_template.ipynb --to slides --post serve --template output_toggle