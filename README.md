# Spotify Data Retriever
A collection of functions in a jupyter notebook wrapping spotipy functions and API calls to get general data or your own user data on songs, artists, playlists, etc. 

You will need API creditials to be able to use the any of the functions in the notebook. Here is how to get those credentials:

1. Sign up for a 'Spotify for Developers' account at https://developer.spotify.com/dashboard/
  - Navigate to your dashboard and select "Create an app".
  - Create your app with a name and description. This is just to get the Spotify API credentials.
2. Save your Client ID and Client Secret ID as environment variables as "spotifyClientId" and "spotifyClientSecret" on your computer. Or you can save them to paste into the notebooks if you prefer
  - [Instructions to set environment variables on Windows](https://docs.oracle.com/en/database/oracle/r-enterprise/1.5.1/oread/creating-and-modifying-environment-variables-on-windows.html#GUID-DD6F9982-60D5-48F6-8270-A27EC53807D0)
  - [Instructions to set environment variables on Mac](https://medium.com/@youngstone89/setting-up-environment-variables-in-mac-os-28e5941c771c)
  
To be able to run some of the wrapper functions which call Spotipy functions, you will need the Spotipy package installed. Instructions on how to get it are [here](https://spotipy.readthedocs.io/en/2.16.1/#installation). 

Enjoy!
