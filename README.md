# Spotify_Playlist_Analysis

Attempting to predict song recommendations for a given playlist - similar to concept behind Spotify's 'Smart Shuffle' feature. 

Stages:

## Data Collection
This phase was concerned with building the data source that I could extract insights from. There were two parts needed in this data souce:
- Playlists containing Songs
- Audio Features for each Song

I got the first part from the million playlists challenge [here](https://www.aicrowd.com/challenges/spotify-million-playlist-dataset-challenge). This held the playlist:song relation in JSON format that I was able to parse and create the first part of the dataset from.
The second part of this data was the audio features for each song. Audio features were needed to relate songs to each other. Ex.) Songs with similar loudness, energy, danceability levels have a higher relation to each other. This audio features data was extracted using [Spotify's Web API](https://developer.spotify.com/documentation/web-api). By calling the API with song IDs existing in the first part of the playlist, a finalized dataset could be built with songs, the playlist a song belonged to, and the audio features of songs. 

## EDA

## Model Training
