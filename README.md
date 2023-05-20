# Song-Popularity-Analysis-Prediction

Objective#
In the below analysis you will find some detailed EDA on what makes a song popular and hypothesis testing for giving any sort of inference from a Statistical point of view. The objective of conducting this analysis was to build a robust model to predict the popularity of a song based on several attributes like energy, acoustics, tempo, liveness, danceability, as well as to understand how these features impact it.

For more details check out the notebook

About Dataset
Introduction
Spotify for Developers offers a wide range of possibilities to utilize the extensive catalog of Spotify data. One of them are the audio features calculated for each song and made available via the official Spotify Web API.

This is an attempt to retrieve the spotify data post the last extracted data. Haven't fully tested if this spotify allowed any other API full request post 2019

About
Each song (row) has values for artist name, track name, track id and the audio features itself (for more information about the audio features check out this doc from Spotify).

Additionally, there is also a popularity feature included in this dataset. Please note that Spotify recalculates this value based on the number of plays the track receives so it might not be correct value anymore when you access the data.

Key Questions/Hypothesis that can be Answered

ARE SONGS IN MAJOR MODE ARE MORE POPULAR THAN ONES IN MINOR?
ARE SONGS WITH HIGH LOUDNESS ARE MOST POPULAR?
MOST PEOPLE LIKE LISTENING TO SONGS WITH SHORTER DURATION?
In addition more detailed analysis can be done to see what causes a song to be popular.

Credit
Entire Credit goes to Spotify for providing this data via their Web API.

https://developer.spotify.com/documentation/web-api/reference/tracks/get-track/
