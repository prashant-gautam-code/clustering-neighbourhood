# Segmenting and Clustering Neighborhoods in Toronto
1. The data collection is done by scraping wikipedia page : https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M. The table from the page with Postcode, Borough and Neighbourhood is used to create a DataFrame.

2. In this step we append the geographical coordinates to the DataFrame, unfortunately using Geocoder did not work for me so I used CSV file to load the coordinates. 

3. Clustering the neighbourhoods with "Toronoto" in their names on a map is done us folium map. The data was encoded, sorted for top 10 most popular places and clusters were defined.

