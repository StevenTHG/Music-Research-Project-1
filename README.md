# Music-Research-Project-1

### Members:
Alexis Valdez  
Brian Lee  
Bruce Chang  
Chika Okam  
Ivan Villa  
Lissette Escobedo  
Tuan Huang  

## Project Description: 
Looking into the trends and popularity of music on the internet. Past and current music trends and commercial success of certain songs and genres can serve as significant indicators of future popularity. There are many phases in music where specific genres can be more popular than others. In these phases, the popular genres will tend to provide more song appearances in music and music popularity tracking platforms such as Napster, Spotify, and LastFM. In this project, we examine the correlation of  music genre, genre popularity, and their musical elements in  predicting  future commercial music success.

### Research Questions to Answer:
Understand the trend of internet music over time by using scatter plots, bar charts, and multiple line graphs etc.

Find the correlation between musical elements such as BPM and popularity  
How music popularity has changed over time  
How are musical elements changing over time  
Determine the genre of music that will be the most popular in the future  



### Breakdown of Tasks:  
Start by pulling info from our API sources  
Separate APIs into different branches for team members to work on  
Extract relevant info such as artist, genre, etc.  
Clean and collect data that will go into dataframes  
Use dataframes to plot and examine trends  
Perform statistical analysis  
Answer our research questions  

# Conclusion/Statistical Analysis

With an interest in music we decided to answer a couple questions regarding the change of different musical elements and trends of music popularity over time. One question we wanted to answer was whether there was a correlation between musical elements and popularity. Along with that question, we wanted to know how musical elements were changing over time. Some musical elements we looked at were BPM, duration, danceability, valence, and energy. On top of all that, we also explored the genre of music that would be the most popular within a few years.  

A significant finding we discovered through Spotify data was that there was no correlation between the popularity of a song and beats per minute (BPM) since the correlation was 0.0. This in itself shows that no matter how fast or slow a song is performed- it does not affect its popularity. Furthermore, music and music creation is getting more popular as the years go on because from 2011 to 2020 the number of tracks released has increased steadily. This could be due to social media platforms such as tiktok; since many artists get discovered by their songs getting popular through snippets in a Tiktok video.  

Moving on to the different musical elements we looked at: duration, danceability, valence, and energy. We found that the duration of songs is getting shorter as the years go on. Danceability on the other hand is increasing as the years go on. Again, this could be affected by the rise of TikTok/TikTok dances and its short duration which could compel artists to create shorter catchy songs in an attempt to go viral. The valence level of songs, however, is not changing much as the years go on.   

Lastly, we looked at the top 10 songs by genre and discovered that pop dominated the charts over the past decade. However, it is worth mentioning that edm has been growing in popularity. Also, additional research into LastFM’s tag statistics shows that significantly more people use the rock tag over pop. It should be noted that LastFM is a much smaller platform than Spotify and the statistics we gathered from it only explain a small portion of a genre’s popularity. With all of this information, it can be expected that pop will continue to be popular over the decades to come.

# Link to presentation
https://docs.google.com/presentation/d/1FZrmm_oKfUI4IZfeEv3Ej2VLDVlQahqPfclt4kaYn7M/edit?usp=sharing
  
## Code Sources
How to get artist URI in Spotify:
https://stackoverflow.com/questions/69657907/how-to-get-uri-of-the-artist-from-spotify-without-having-to-manually-copy-the-ur
 
Accessing Spotify API in Python:
https://stmorse.github.io/journal/spotify-api.html

Spotipy Documentation:
https://spotipy.readthedocs.io/en/2.21.0/#ids-uris-and-urls

LastFM Documentation:
https://www.last.fm/api/show/chart.getTopTags
https://www.last.fm/api/show/tag.getInfo

### Spotify Song Statistic Definitions Sources

https://towardsdatascience.com/is-my-spotify-music-boring-an-analysis-involving-music-data-and-machine-learning-47550ae931de

https://www.theverge.com/tldr/2018/2/5/16974194/spotify-recommendation-algorithm-playlist-hack-nelson

### Dataset Sources
Spotify 1.2M+ Songs: https://www.kaggle.com/datasets/rodolfofigueroa/spotify-12m-songs?resource=download

Top Spotify songs from 2010-2019 - BY YEAR:
https://www.kaggle.com/datasets/leonardopena/top-spotify-songs-from-20102019-by-year
