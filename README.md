# INFM600-InformationOrganization
=================================
Rotten Tomatoes Ratings by Genres
=================================

--------------------
Original Dataset
--------------------

This dataset is a subset of the hetrec2011-movielens-2k dataset, published by GroupLens. 

URL: http://files.grouplens.org/datasets/hetrec2011/hetrec2011-movielens-2k-v2.zip

The original dataset contained 12 .dat files combining data from:
- the MovieLens10M dataset (http://files.grouplens.org/datasets/movielens/ml-10m.zip) 
- Internet Movie Database (IMDb)(http://www.imdb.com)
- Rotten Tomatoes (http://www.rottentomatoes.com)

The dataset was prodcued as part of the HetRec'11 workshop
@inproceedings{Cantador:RecSys2011,
      author = {Cantador, Iv\'{a}n and Brusilovsky, Peter and Kuflik, Tsvi},
      title = {2nd Workshop on Information Heterogeneity and Fusion in Recommender Systems (HetRec 2011)},
      booktitle = {Proceedings of the 5th ACM conference on Recommender systems},
      series = {RecSys 2011},
      year = {2011},
      location = {Chicago, IL, USA},
      publisher = {ACM},
      address = {New York, NY, USA},
      keywords = {information heterogeneity, information integration, recommender systems},
   } 

The data contained in hetrec2011-movielens-2k.zip is distributed with permission of GroupLens research group. The data is made available for non-commercial use.

         
--------------------
New Dataset - Rotten Tomatoes Ratings by Genres.xlxs
--------------------

From the original dataset, only three of the twelve .dat files were used: movies.dat, movie_genres.dat, and movie_countries.dat. The movie_genres file was modified to show all genres related to a specific movieID on one row of data. The three files were then combined into 1 file. The file was then reviewed for invalid or missing ratings, number of reviews, or score. Movies with invalid or missing data were stripped from the dataset.

The dataset plus detailed step by step instructions of how this file was created can be found on the URL listed below.

URL: https://github.com/focolman/INFM600-InformationOrganization 
   
This file contains the following information:
- id - This is the movie id from MovieLens
- title - This is the movie title
- rtAudienceRating - This is the average audience rating from RottenTomatoes.com. This number should be between 1-5.
- rtAudienceNumRatings - This is the number of audience reviews on RottenTomates.com for a particulart movie
- rtAudienceScore - This is the audience score from RottenTomatoes.com. This number should be between 1-100.
- country - This field lists the movies country of origin
** The following 20 fields contain either a 'YES' or 'NO' value to indicate if the movie was part of that genre.
- Action 
- Adventure 
- Animation
- Children
- Comedy
- Crime
- Documentary
- Drama
- Fantasy
- Film-Noir
- Horror
- IMAX
- Musical
- Mystery
- Romance
- Sci-Fi
- Short
- Thriller
- War
- Western 

--------------------
Question that the subset of data can answer
--------------------

By country of origin what genres of movies do users review most favorably? This is a very important question as it helps movie producers understand the genre preferences in different countries.

--------------------
License
--------------------

This work is licensed under a Creative Commons Attribution-NonCommercial 4.0 International License.

--------------------
Citation
--------------------

Alluru, R., & O'Colman, F. (2015, March 8). Rotten Tomatoes Ratings by Genres. Retrieved from https://github.com/focolman/INFM600-InformationOrganization

--------------------
Wiki
--------------------

Username: Focolman
URL: http://wiki.urbanhogfarm.com/index.php/Rotten_Tomatoes_Ratings_by_Genres
