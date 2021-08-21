The folder contains the 3 .csv file, 1 .txt file and 1 jupyter notebook.
The project is to calculate the data of movies from imdb.

The data is extracted using "imdbpy" api module written in python.

The final data is present in the "final_file.csv" file. The data present in the file is:
1. Movie Title - Contains the title of the movies.
2. movie_id - Contains the id of the movie as present in the imdb site.
3. release_date - Contains the Date/year of the release of the movie.
4. genres - Contains the genre of the movie.
5. casts - Contains the names of the actors and actresses casted in the movie.
6. directors - Contains the names of directors who directed the movie.
7. writers - Contains the names of writers who wrote the movie.
8. producers - Contains the names of producers who produced the movie.
9. plot_summary - Contains the summary of the plot of the movie.
10. votes - Contains the number of the votes a movie get on the imdb site.
11. rating - Contains the imdb rating of the movie.
12. time_of_content(days) - Contains the time in days since the release of the movie 
                            until 20-August-2021.
13. popularity_of_content - Contains the popularity of the content which is calculated using
                            the 'votes' and 'rating' columns.

The 'popularity_of_content' is calculated using the formula:
----> rating * z-score(votes)

The "target_movies.csv" file contains the same details as in "final_file.csv" except the 'time_of_content(days)' and 'popularity_of_content' columns.

The "requirement.txt" file contains the required module names to run the jupyter notebook "Assignment.ipynb".
The "Assignment.ipynb" file contains the code to get the data from only the title of the movie whihc are present in the "movies.csv" file.

-------------Thank You-----------------