# Movie Recommendation Systems
This repository contains three types of movie recommendation systems using the TMDB Movie Metadata and The Movies Dataset from Kaggle:

+ Demographic Recommendation System
+ Content-Based Recommendation System
+ Collaborative Filtering Recommendation System

# The Age of Recommender Systems¶
The rapid growth of data collection has led to a new era of information. Data is being used to create more efficient systems and this is where Recommendation Systems come into play. Recommendation Systems are a type of information filtering systems as they improve the quality of search results and provides items that are more relevant to the search item or are realted to the search history of the user.

They are used to predict the rating or preference that a user would give to an item. Almost every major tech company has applied them in some form or the other: Amazon uses it to suggest products to customers, YouTube uses it to decide which video to play next on autoplay, and Facebook uses it to recommend pages to like and people to follow. Moreover, companies like Netflix and Spotify depend highly on the effectiveness of their recommendation engines for their business and success.

In this kernel we'll be building a baseline Movie Recommendation System using TMDB 5000 Movie Dataset from Kaggle. For novices like me this kernel will pretty much serve as a foundation in recommendation systems and will provide you with something to start with.

There are basically three types of recommender systems:-

+ Demographic Filtering- They offer generalized recommendations to every user, based on movie popularity and/or genre. The System recommends the same movies to users with similar demographic features. Since each user is different , this approach is considered to be too simple. The basic idea behind this system is that movies that are more popular and critically acclaimed will have a higher probability of being liked by the average audience.
  ![image](https://github.com/DanBeverley/Recommendation-System/assets/161696810/df9ed3f4-c033-475c-9561-2e66168eea72)

+ Content Based Filtering- They suggest similar items based on a particular item. This system uses item metadata, such as genre, director, description, actors, etc. for movies, to make these recommendations. The general idea behind these recommender systems is that if a person liked a particular item, he or she will also like an item that is similar to it.
  ![image](https://github.com/DanBeverley/Recommendation-System/assets/161696810/c6152417-077f-4cee-8695-a6ca74ffe0e1)

+ Collaborative Filtering- This system matches persons with similar interests and provides recommendations based on this matching. Collaborative filters do not require item metadata like its content-based counterparts.
  ![image](https://github.com/DanBeverley/Recommendation-System/assets/161696810/fc1089cb-52b5-47cd-b388-664406ceb92a)

# Results
The results and evaluations of the recommendation systems can be found in the respective notebooks.

# Contributing
Contributions are welcome! Please open an issue or submit a pull request for any changes or improvements.

# Acknowledgements
The datasets used in this project are from Kaggle: TMDB Movie Metadata and The Movies Dataset.
Special thanks to the Kaggle community for providing these datasets.


