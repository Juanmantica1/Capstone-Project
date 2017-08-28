# MileStone Report

In order to make movies, producers have to invest large amounts of time and money. However, while the movie business has grown to be multi-billion dollar market, there is little to no statistical metrics regarding the probability of success for a movie, and, therefore, little to no knowledge on the rate of return that a movie will bring. In order to help producers take on a more professional and scientifical approach to the movie business I have decided to create a predictive model on movie success. 

For that reason, I have tasked myself with using a database of 5000 movies created by another data science student (Chuan Sun) from the New York Data Science Academy, in order to create a regression that deals with the dollar gross budget of a movie.

While, Chuan Sun's dataset was helpful it was from perfect as it had missing values for the 'movie_gross' column of the data set and the values included in the column were not calculated for inflation and were not normalized to US dollars. Therefore, I used the python packages: pandas and easypeasy, in order to deal with null values and normalize the data for predictive modeling. 
Eventhough, Chuan Sun's dataset has been cleaned and wrangled there are other databases in the imdb interface, that could further help me classify the features in the database.
So far, from inferential statistics I have derived that the feature that is most strongly linked to a movie's gross is, not supringsily, the movie's budget. The movie's gross is strongly related to the order of magnitude(log10) of the movie's budget, with an r2 value of .4.
