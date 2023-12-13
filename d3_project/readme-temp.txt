DESCRIPTION
The tool allows you to explore the features of popular songs based on region and make predictions about the success of songs based on those features.
It is based on two Spotify datasets and relies on both our analysis and model API.
The front-end folder contains D3 code for the visualization and csv files summarizing the results of our analysis. The D3 visualization also connects to our API to make predictions.
The back-end folder contains our data exploration, analysis, and model results.
Please note that our tool has only been tested in Chrome and is not designed for devices smaller than 1100px.

Additional Resources:
Code for Front-End: https://github.gatech.edu/kcozart6/kcozart6.github.io
Code for Back-End: https://github.gatech.edu/pwu318/6242Project

INSTALLATION
There are two usage options. 
(1) Use our tool at: https://github.gatech.edu/pages/kcozart6/kcozart6.github.io/
(2) Follow these instructions to download and run:
(a) Start a server:
Python 2 — python -m SimpleHTTPServer 8000
Python 3 — python -m http.server 8000
(b) In browser, navigate to http://localhost:8000/
(c) Navigate to location of downloaded files
(d) Open index.html

EXECUTION
Mouse over different countries in the map to see country-specific data under the map legend.
Use the dropdown to select different regions to analyze. The components below the map will update based on your selection.
The line chart shows some of the most important overall features and their values over time.
The bar chart shows the feature importance using MDI.
The table shows what features an ideal song would have in the selected region at the top. It also shows the 5 most popular songs in that region and some of their features.
The form component shows ranges of acceptable values for each feature and allows you to input features and predict the success of a song with those features.