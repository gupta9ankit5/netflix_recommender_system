# netflix_recommender_system
Predicting user ratings on unseen movie which can be used in recommending movies to users

<h2> Problem Statement </h2>
Netflix provided a lot of anonymous rating data, and a prediction accuracy bar that is 10% better than what Cinematch can do on the same training data set. (Accuracy is a measurement of how closely predicted ratings of movies match subsequent actual ratings.)

Sources
  https://www.netflixprize.com/rules.html
  https://www.kaggle.com/netflix-inc/netflix-prize-data
  
  
<h3> Business Objectives and constraints</h3>

  Objectives:
    Predict the rating that a user would give to a movie that he ahs not yet rated.
    Minimize the difference between predicted and actual rating (RMSE and MAPE)
  
  Constraints:
    Some form of interpretability.

<h3>Data files :</h3>

  combined_data_1.txt
  combined_data_2.txt
  combined_data_3.txt
  combined_data_4.txt
  movie_titles.csv
  
  Refer : https://www.kaggle.com/netflix-inc/netflix-prize-data/data
  
  
<h3>Prerequisites</h3>

  1. Sparse matrices (https://docs.scipy.org/doc/scipy/reference/sparse.html)
  2. SVD and Truncated SVD (https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.TruncatedSVD.html)
  3. Surprise baseline models http://surpriselib.com/

<h3> There is a single ipynb file with the name Netflix_Movie.ipynb </h3>
