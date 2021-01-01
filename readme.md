# FordGoBike
### by Ahmed_Adel_Hekal

##### You can see the conclusion of a study by opening explanatory.slides.html which is slide summarize study 14

### Introduction
 Ford GoBike is a regional public bicycle sharing system in the San Francisco Bay Area, California. Beginning operation in August 29th 2013 as Bay Area Bike Share, the Ford GoBike system currently has over 2,600 bicycles in 262 stations across San Francisco, East Bay and San Jose. From it's early development, many other cities began adopting this system.
 This is the link for the dataset https://s3.amazonaws.com/fordgobike-data/index.html. This data set includes information about individual rides made in a bike-sharing system covering the San Francisco Bay area.
Our goal as a data analyst, is to increase it's rideship and to offer deals through the mobile app. What deals can be offered? Currently, it has three options: a flat price for a single one-way trip, a day pass that allows unlimited 30-minute rides for 24 hours and an annual membership. In addition to using bicycles, Ford has introduced electric bikes called Ford GoBike Plus (ebike) https://www.fordgobike.com/how-it-works/meet-the-bike.
Some of the questions that would be good to answer are:
>* who is more likely to use the service (customer or subscriber)  ? 
>* Which gender is more likely to ride a bike ? 
>* which station is more frequent to start the trip from and which is for end of the trip  ?
>* Is there is a relation between age & gender ?

The Data Structure are as follows:
Each trip is anonymized and includes:

 * Trip Duration (seconds)
 * Start Time and Date
 * End Time and Date
 * Start Station ID
 * Start Station Name
 * Start Station Latitude
 * Start Station Longitude
 * End Station ID
 * End Station Name
 * End Station Latitude
 * End Station Longitude
 * Bike ID
 * User Type (Subscriber or Customer )
 * Member Year of Birth
 * Member Gender

## Summary of fidings

Most users are male
adults  users are most users  .
service mostly used for short durations(which mean short distanse).
youth tends to bike_share_for_all _trips unlike adults
Other gender tend to use service as subscribers more than customers
*For customers :.
1- Most customers use service between 7~18 minutes.
2- Most of customer have age between 27~ 32.
For subscribers :.
1- Most subscribers use service between 5~12 minutes.
2- Most of subscribers have age between 25~ 36.

for top 10 stations:. 

1- top10 station is differ from  subscribers to customers ,which mean for some reason people in some areas prefer to use our service but not join with us.

1- Males ride for long time , Female riders are younger than Male ,
older males use servies for long period of time compare to females in same age


## Key insight for presentation 

first, instead of dealing with the dataset as one block .my idea was to split data using some useful criteria. so I divided data depending on user_type. which makes it easier to get relations in data. so I used histograms to find that majority of users are males .then using boxplot I found a lot of outliers so I dropped it. then using countplot to find which data is most frequent. scatter to find the relationship between features. then I used size encoding to find the relation between 3 features which lead to an ambiguous result. so I used color encoding.
