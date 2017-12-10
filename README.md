# Spotify-Data-Scraper

## Description
A tool for accessing all of an individual's top songs, recently played songs, and playlists on Spotify. It provides convenient access to music metadata, including tempo, loudness, and number of plays. All this data is exported as a CSV, able to be imported into any data analysis program like Excel.

## How to use?
python spotify.py username

Because it was made using functional programming, you can modify the tool to suit your data collection needs! See the Spotify API Endpoints for the data you can collect.

The functions I have created are:

my_top_tracks(username,N) => see N top tracks outputted in Excel and their attributes
tracks_by_time(username,N) => see the timestamps for your past N tracks outputted in Excel and their attributes
read_dailyMix(username) => see the songs in your daily mix and their attributes
Feel free to use these, comment them out, or create your own!
