# Movie-Recommendation-Systems
This Project carried out  in VIT Vellore for the for the Course Bigdata Analytics(SWE2011).
This Project, I have built 4 different recommendation engines based on different ideas and algorithms. 
They are as follows:
Simple Recommender: This system used overall TMDB Vote Count and Vote Averages to build Top Movies Charts, in general and for a specific genre. The IMDB Weighted Rating System was used to calculate ratings on which the sorting was finally performed.
Content Based Recommender: We built two content based engines; one that took movie overview and taglines as input and the other which took metadata such as cast, crew, genre and keywords to come up with predictions. We also deviced a simple filter to give greater preference to movies with more votes and higher ratings.
Collaborative Filtering: We used the powerful Surprise Library to build a collaborative filter based on single value decomposition. The RMSE obtained was less than 1 and the engine gave estimated ratings for a given user and movie.
Hybrid Engine: We brought together ideas from content and collaborative filterting to build an engine that gave movie suggestions to a particular user based on the estimated ratings that it had internally calculated for that user.

Files:
credits.csv: https://drive.google.com/file/d/1UbRKX-0A4I7izxViJgPjLprKK9IilIHM/view?usp=sharing
