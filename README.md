# GNOD-Song-Recommender

## Lab | Unsupervised learning intro (GNOD - part 4)
### Instructions
It's the moment to perform clustering on the songs you collected. Remember that the ultimate goal of this little project is to improve the recommendations of songs in the hope that the user will enjoy the new song.. Clustering the songs will allow the recommendation system to limit the scope of the recommendations to only songs that belong to the same cluster - songs with similar audio features.

The activities you did with the Spotify API and the PopVortex web scraping will allow you to create a pipeline such that when the user enters a song, you:

1. Check whether or not the input song is in the PopVortex Hot 100.
2. Recommend another Hot 100 song
3. If it is NOT in the hot 100, then collect the audio features from the Spotify API for the input song.
4. You want to send the Spotify audio features of the submitted song to the clustering model, which should return a cluster number.
5. Then you recommend a song from the same cluster number.

Your model will be even more accurate the more songs you use to create your clusters in your model, so you want to have as many songs as possible to create the clustering model.
