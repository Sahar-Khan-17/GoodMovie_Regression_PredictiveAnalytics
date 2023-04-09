# GoodMovie_Regression_PredictiveAnalytics

# Objective : 

What makes a Movie Great? The primary goal of our analysis is to identify what it means for a movie to be called ‘good’ or ‘bad’

# Overview : 

The data points that we selected as a base factor in determining whether a movie is considered good or
bad were user-ratings and revenue. Our definition of a ‘good’ movie is a movie that has a rating score of
6 or higher and a verdict set to 1 for such movies. Any movies with a rating score lower than 6 are ‘bad’
movies and a verdict is set to 0 for those. We also considered the effects of other data points in the dataset
that contribute to a poor rating score and hence classify a movie as ‘bad’. These data points include, but
are not limited to, movie meta data such as the director, production house, runtime, and popularity. Also,
including the associated data points and their effect on ratings score helped us in building a robust model for
predicting whether a movie was ‘good’ or ‘bad’. All the other data points are compared to our base data
points in determining which factors have the most influence on a movie’s rating score.

# Selected Outputs:
 ![probability](https://user-images.githubusercontent.com/116682872/230789375-a5a14bae-c4d6-4a87-ab5f-a97c943b43fc.png)

![score](https://user-images.githubusercontent.com/116682872/230789490-11405522-0072-47d5-b4c1-bb30b2ef65da.png)

![rating-pop-collection](https://user-images.githubusercontent.com/116682872/230789497-dba9b941-5e1a-47fc-a2b2-151359034a85.png)

![ratings](https://user-images.githubusercontent.com/116682872/230789504-aa3b83f9-8a13-4dd8-88ab-7f209de89cd7.png)

![revenue-populartity](https://user-images.githubusercontent.com/116682872/230789507-38fa662e-72a7-4347-b77d-7b364fe7e115.png)

![populairty](https://user-images.githubusercontent.com/116682872/230789513-a053f2a4-7100-40cb-a160-74fa21970758.png)


# Recommendations : 

Our goal was to build a model that could predict the success of a movie based on various factors. We found
that there are several important factors that can greatly influence a movie’s success. In comparison with
cast and director that certainly add value, they both often come at a high cost. In our model, we found
that having a great director had a stronger impact than the cast and production, which could be a balanced
trade-off between expense and success factors.
In addition, there are other good factors that contribute to the success of the movie:
1) Run time between 75-150 minutes
2) Genres: Revenue model - Animation, Comedy, Action, History and Science Fiction Rating model -
Family, drama, action, and documentary Good tradeoff - Action movies
3) Popularity: Popular movies made it to the list of high rated movies. Thus, movies should be very well
marketed or advertised
