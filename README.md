# Project Description
App that extracts song features from a Spotify playlist. The purpose of this project is to visualize the distribution of song features in a given playlist. This projects communicates with the Spotify API to read playlist data, extracts quantitative song features(like tempo, acousticness etc..) and plots the figures using matplotlib.

## Modifications
To analyze your own playlist, replace "client_id" and "client_secret" with your crendentials from the [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/). You can also change the type of playlist you want to analyze. To do that, modify the arguments that the "user_playlist" functions takes. The first argument is the first 11 digits of your [profile link](https://community.spotify.com/t5/Accounts/how-do-i-find-my-spotify-user-id/td-p/665532). The second argument is the playlist link. Copy everything after open.spotify.com/playlist/ from the web browser to get the playlist link.  
