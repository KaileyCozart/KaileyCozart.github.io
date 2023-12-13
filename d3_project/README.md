## Predicting Song Virality by Region

##### This tool allows you to explore musical data by region as well as predict how likely your song will be a chart topper given the characteristics of a song that Spotify gives you. The top visual shows the relevant countries per region we analyzed as well as the peak number of streams for a song for each country. The line chart shows the average of the top 3 features by feature importance over time. The bar chart shows the feature importance of each different model. The table below shows some relevant features of the top 5 songs in that region. Finally, the bottom visualization allows users to input features of a song and predict how likely it will be viral in the selected region. This portion of the visualization is connected to our back-end model via an api.

### Useage Options:

##### Website: https://github.gatech.edu/pages/kcozart6/kcozart6.github.io/

##### Download and Run: 
###### Python 2 — python -m SimpleHTTPServer 8000
###### Python 3 — python -m http.server 8000
###### Navigate to http://localhost:8000/ and then location of downloaded files, open index.html

### Limitations:
###### Only tested in Chrome
###### Not designed for devices smaller than 1100px

### Back-End and API:
###### Code for Back-End: https://github.gatech.edu/pwu318/6242Project
###### payload = {"features": [danceability, energy, key, loudness, mode, speechiness, acousticness, instrumentalness, liveness, valence, tempo, time_signature]}
