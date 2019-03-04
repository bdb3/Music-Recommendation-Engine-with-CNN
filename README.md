# Music-Recommendation-Engine
Using song analysis data to find recommendations for music with low user interaction



Initially the songs in the Million Song Database (MSD) were clustered with k-means clustering and each entry was labelled with the cluster number.d
Then, after clustering into 10,25,50,75,100,200,300,400,500,800, and 1000 clusters, and using this cluster number as a label, a CNN is trained. 
When a user opens the reccomendation app, they query the Spotify API for a song that they want similar songs reccomended for using a text box.
Then the API returns song analysis data that matches the features of the MSD, thus the CNN can output a cluster number that the song most closely matches with. 
