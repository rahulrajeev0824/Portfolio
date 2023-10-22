This was a machine learning introductory experience understanding what attributes of a movie determine its rotten tomato score. 
Attributes include director, writers, genre, length, and rating to name a few. 
Most of the challenges in this project revolved around data formatting as there were many formats for each column. 
The project used regression, but under the time constraints, I didn’t get to apply gradient boosting to the algorithm. 
Perhaps I can circle back on this another time, most like the other projects as well.

Loading Data:
Please find and download the data from the source at:  
https://www.kaggle.com/datasets/andrezaza/clapper-massive-rotten-tomatoes-movies-and-reviews?select=rotten_tomatoes_movies.csv

The files were too large to upload to GitHub

Implementation:
The transformed csvs that were used for modeling are all created by the notebook. I left checkpoints in the code so that after each time consuming step
the csvs are saved to some differently named csv. That way the project can be picked up whenever without going through everything again. Be
sure to comment out code that you wouldn't need to run many times.