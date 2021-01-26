# Location selection for a new fast food restaurant

This repository developed a solution to pick the most suitable location for a new fast-food restaurant.We obtained datasets from different resources. 
The city's region list was scraped from the Wikipedia Page, Geo-coordinates of regions were obtained with the Google Maps Geocoding API and we used the Foursquare API to obtain the most visited restaurant categories and the number of restaurants belonging to different types in each borough of Berlin.

We used Python package sci-kit learn while building K- means clustering model after selecting the most appropriate cluster number using SSE and elbow point method.Based on the clustering results, we made recommendations regarding the best region for a new fast-food restaurant in Berlin.
