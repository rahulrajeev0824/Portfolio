Restaurant recommendation system that uses collaborative filtering and content-based filtering to recommend restaurants to users.
The collaborative filtering uses reviews of restaurants based on service, food, and overall. The content-based filtering takes into account the users preference before selecting restaurants. The system is built on Nearest Neighbor cosine similarity for the review and preference vectors.

Downloading data:
https://archive.ics.uci.edu/dataset/232/restaurant+consumer+data

The data is centered around restaurants in Mexico, but I think with time, other restaurants can be added to use similar methodology to recommend international restaurants.

Implementation:
Visualizations and early data analysis were done using the csv files. The recommendation system is built inside a class
with methods to be called for different purposes. Methods can be added and the nearest neighbor model can also be tuned.
To actually run the recommendation system you will have to initialize the class and then run the different methods on top of it.