# adjusted-country-centroids

Geoloc providers use coordinates for country centroids, which sometimes (often?) are at people's postal addresses.
These people receive a lot of abuse etc. for websites and IP addresses that geoloc to this centroid.

This is an attempt to create a country centroid dataset that has coordinates that are relatively close to the 
centroid of a country but can't be confused for postal addresses. Bodies of water, etc. are good places to put these.

If you have a centroid that you like to move, please add it to the centroids.csv file

If we have enough centroids, we can try convince geoloc providers to start using these alternatives.

Background:
Problems for a farmer in NL: https://nos.nl/artikel/2365293-dronter-gezin-al-jaren-bedreigd-vanwege-geografische-coordinaten.html
USA centroid: TODO find this news item
