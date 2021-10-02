# Team The Coup Starts Now's Song Feature Analysis

This repo contains the Fall 2021 semester project for team The Coup Starts Now for the Data Mining class at SJSU. The members of team The Coup Starts Now are:

* Jordan Conragan (JVP15) 
* Jason Liu (jasonliu96) 
* Kanak Kshirsagar (Kanak17)


# Dataset

We are doing our analysis on [Spotify Multi-Genre Playlist Data](https://www.kaggle.com/siropo/spotify-multigenre-playlists-data) which was collected by Kaggle user Ido Lior and falls under the [Community Data License Agreement - Sharing - Version 1.0](https://cdla.dev/sharing-1-0/). This dataset is a collection of song features taken from Spotify and separated into six broad genres of music. It is not a random sampling of songs on Spotify: each song was on a playlist made by the person who collected the dataset. However, there is still a wide variety of genres it will work for purposes of our analysis. The dataset has the following 22 columns:

1. Artist Name
2. Song Name
3. Popularity: value from 1 to 100 that represents the song's popularity (magically determined by Spotify)
4. Genres: a detailed list of the genres for each artist
5. Playlist: the name of the playlist each song came from
6. Danceability
7. Energy
8. Key
9. Loudness
9. Mode
10. Speechiness
11. Acousticness
12. Instrumentalness
13. Liveness
14. Valence
15. Tempo
16. ID
17. URI
18. HRef
19. Analysis_url
19. Duration_Ms
20. Time-Signature

# Problem

The primary problem we want to solve is: how does the genre of each song correspond to the audio features extracted by Spotify? 

## How will we solve it?

We will start by creating graphs based on our dataset. We may be able to visually find patterns in our data that we can further explore through mathematical means such as Pearsons Correlation. We will also experiment with using a Support Vector Machine (SVM) to predict the genre of a song based on its features.

## How is success defined? 

This project will be successful if we can find a correlation between the genre of a song and its audio features. It will be a complete success if we are able to do this for the 6 major genres of music present in the dataset, but we will take it as a win if we can find correlation between a song's genre and audio features for a single genre. 
