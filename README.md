# CodeClause_Movie_Recommendation_System
In this machine learning project, we build a recommendation system from the ground up to suggest movies to the user based on his/her preferences.
We have used a dataset that contains the metadata (cast, crew, budget, etc..) of the movie.

# Tools and Libraries used
1. Python
2. Pandas
3. Scikit-learn

In this project, we have used a Content-based recommendation engine for movies.

# Steps followed for building this system are as follows:
1. Perform Exploratory Data Analysis (EDA) on the data
2. Build the recommendation system
3. Get recommendations

# About Datasets:
The dataset contains two CSV files: Credits, and Movies. 
The credits file contains all the metadata information about the movie and the movie file contains the information like name and movie_id of the movie, budget, languages in the movie that has been released, etc.

# Steps followed for making recommendation system:

1. Get the index of the movie using the title.
2. Get the list of similarity scores of the movies concerning all the movies.
3. Enumerate them (create tuples) with the first element being the index and the second element is the cosine similarity score.
4. Sort the list of tuples in descending order based on the similarity score.
5. Get the list of the indices of the top 10 movies from the sorted list. Exclude the first element because it is the title itself.
6. Map those indices to respective titles and return the movies list.

# Result:
![Screenshot (93)](https://user-images.githubusercontent.com/77968630/209291345-dbeac0ed-357c-44f5-860a-a6a75b65e567.png)


# Summary:
In this machine learning project, we build movie recommendation systems. 
We built a content-based recommendation engine that makes recommendations given the title of the movie as input.
