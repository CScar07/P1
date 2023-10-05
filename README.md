Summary of Spotify Data
Group 1
Alysa S., Chase S., Hayden J., Jimmy C., Dianna R.

Our data is comprised of music on Spotify’s music platform over 23 years. We have compressed this data to look at the years 2010-2023 and view popular songs with a popularity index score of 85. 

The main things we want to address are what is the relationship of genres vs. popularity, popularity vs. years and what correlation is there (if any) of song attributes over the years.

When looking at the most popular genres appear to be pop, hip-hop, and dance.

![image](https://github.com/CScar07/P1/assets/129472048/6273bd49-d75c-4e0d-b6c6-20d7ba1cacdc)

 
When looking at the bottom 5 genres we see that the lowest three are songwriter, rock, and Detroit techno. However, the lower 15 genres all fall within the same level. This could be because these genres are very niche. While they could be very popular with fans of those groups looking at a larger scale makes it fall short.    

Moving onto the average popularity score, looking specifically at those with a popularity score over 85, shows some fluctuations as these are based on the number of plays done on Spotify vs. their popularity during its release. 

 ![image](https://github.com/CScar07/P1/assets/129472048/82749a28-ff7e-4c2e-aa7f-57ac47b0ec9e)
![image](https://github.com/CScar07/P1/assets/129472048/dc9e1e8a-8324-4287-bcd0-afc5de920017)

 
It is important to take into consideration “timeless hits” as these songs can rise in popularity depending on users’ play or their relevance in social media/culture. To make these distinctions it would be helpful to look at music events over the years to see if those can cause a rise in playtime. 

When looking at attributes of songs over the years we can see that they all mesh and vary over years/songs. However, certain attributes maintain a higher weight and could contribute to a song’s popularity. Given the large amount of data we are manipulating when trying to find a correlation between all songs we found danceability had the largest positive correlation (coefficient between x and y is 0.14 or y =0.0x + 0.5) and instrumental had the most negative correlation (coefficient between x and y is -0.14 or y =0.0x + 0.31). 

![image](https://github.com/CScar07/P1/assets/129472048/63e60fab-dd21-4865-8ed7-8c5336650ec9)

 
Overall, our data limits us to what is being played on Spotify and does not look into any outside factors that may influence songs to rise in play, Spotify’s algorithm for pushing songs, or the overall popularity of a song (on other platforms or per Billboards charts). 
While we could use the current data to help us curate a popular song this song would be limited to Spotify’s platform, and it would not be easy to know for certain if the song would do well outside of Spotify. 


















# P1
Group_Analysis/Visualization--PROJECT 1
Project title- Music Predictor (working title)

Team members-Alysa S.(opener) Chase S. , Alysa S., Jimmy C., Hayden J., Dianna R.

Project description/outline- What [attributes] make a song successful? Continue to be popular? What song will be popular?

Research questions-  What is the relationship between genre v. popularity ; the relationship between mean popularity over release date, and relationship between attribute scores over the years; relationship between popularity v. specific, described attributes. 

Datasets to be used- https://www.kaggle.com/datasets/amitanshjoshi/spotify-1million-tracks

Rough breakdown of tasks- Clean the dataset by sorting by popularity in a dataframe, removing null rows, converting necessary numeric data; Finding correlation of popularity v. song attributes using summary statistical methods; regression + plotting.

