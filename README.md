# To use the code
You must have a Spotify account in order to get recommendation as this program works on Spotify
first you need to install jupyter notebook and spotipy library.
Go to https://developer.spotify.com/ and create your Spotify developer account.
Then go to https://developer.spotify.com/documentation/general/guides/app-settings/ to create a client and get client_id and client secret. 
Go to https://developer.spotify.com/console/get-current-user/ click on get token and select following scopes from the list:
  1. user-library-read
  2. playlist-read-private 
  3. playlist-modify-public 
  4. playlist-modify-private 
  5. user-library-modify

and then click on request token to create it.
Then open config.cfg file and copy your credentials at required locations.

The program will recommend you song based on the characteristics of your liked and disliked songs.
The characteristics include: danceability, loudness, valence, energy, instrumentalness, acousticness, key, speechiness, and duration.



