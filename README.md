# Netflix-Movies-And-Tv-Shows-Clustering
![netflix-660x330](https://user-images.githubusercontent.com/105944539/192093068-768a84c8-86ec-4c21-baab-d222284984cc.png)

This project is a part of "Unsupervised Machine Learning” curriculum as capstone projects at AlmaBetter School 




Netflix is an American subscriptionstreaming service and production company. It is the one of the largest Platform which provides the collection of TV shows and movies, streaming via online means. The monthly subscription by user makes Netflix a profitable business and the flexibility in subscription users can cancel it anytime. So to engage customers to this platform Netflix must keep their content interesting that can hook users on the platform. That’s why the recommendation system which provides valuable suggestions to users is essential.

                                    Netflix’s recommendation system gives the idea to them about the popularity of their services provides as it helps to increase the sold the subscriptions as more as possible, which offers a varieties of items for selections, this help to get them a user satisfaction,and their loyalty to platform and get them a better understanding of what the user wants.
Then it’s easier to get the user to make better decisions from a wide variety of movie products.

           With over 139 million paid subscribers(total viewer pool -300 million) across 190 countries, 15,400 titles across its regional libraries and 112 Emmy Award Nominations in 2018 — Netflix is the leading Internet television network and the most-valued largest streaming service in the world. The success behind the amazing story of Netflix is incomplete without the mention of its recommender systems that focus on personalization according to users. According to your preferences, there are several methods to create a list of recommendations. You can use (Collaborative-filtering) and (Content-based Filtering) for recommendation.

# Objective

     The project's main goal is to create a model that can perform Clustering on comparable material by matching text-based attributes.

# Dataset Peeping

  The dataset has 7787 rows and 12 attributes to work with. 
1.	We have NaN values in the dataset.
2.	Changed the format of the Date.
3.	Added some columns which are extracted from the Date column.


## Data Description

## Attribute Information:

1.	show_id: Unique ID for every Movie / Tv Show
2.	type: Identifier - A Movie or TV Show
3.	title: Title of the Movie / Tv Show
4.	director: Director of the Movie
5.	cast: Actors involved in the movie / show
6.	country: Country where the movie / show was produced
7.	date added: Date it was added on Netflix
8.	release year: Actual Release Year of the movie / show
9.	rating: TV Rating of the movie / show
10.	duration: Total Duration - in minutes or number of seasons
11.	listed in : Genre
12.	description: The Summary description

# Challenges Faced
 The following are the challenges faced in the data analysis:
 
➢	Conversion of Datetime features, categorical features.
➢	Feature engineering 
➢	Model Implementation


# Tools Used

       The whole project was done using python, in google collab. Following libraries were used for analyzing the data and visualizing it and to build the model to predict the bike count required at each hour for the stable supply of rental bikes. 

●	Pandas: Extensively used to load and wrangle with the dataset.
●	Matplotlib: Used for visualization.
●	Seaborn: Used for visualization.
●	Datetime: Used for analyzing the date variable.
●	Warnings: For filtering and ignoring the warnings.
●	Numpy: For some math operations in predictions.
●	Sklearn: For the purpose of analysis and prediction.
●	Datetime: For reading the date.

# Conclusion-

1.	Most films were released in the years 2018, 2019, and 2020.
2.	TV shows account for 2.8 percent of the total, while movies account for 97.2 percent.
3.	Dramas is a genre that is mostly watched on Netflix and as per audience preference international movies are mostly watched.
4.	The largest count of Netflix content is made with a “TV-14” rating,
5.	The United States, India, the United Kingdom, Canada, and Egypt are the top five producer countries.
6.	Netflix has added a lot more movies and TV episodes in the previous years, but the numbers are still low when compared to movies released in the last ten years.
7.	Movies are mostly watched in various countries rather than TV shows.
8.	We performed data engineering to remove the unnecessary variables and to convert the data into standardized form into scalar.
9.	Implemented model is based on the K-means clustering algorithm consisting of 2,3,4,5,6 clusters.
Silhouette Analysis score for K-means :
•	For n_clusters = 2, silhouette score Is 0.42541313028836003
•	For n_clusters = 3, silhouette score is 0.3940500353920696
•	For n clusters = 4, silhouette score is 0.38498095158183726
•	For n_clusters = 5, silhouette score is 0.3962372504377786
•	For n_clusters = 6, silhouette score is 0.3925658868286329
11.	After clustering, we can say that our alternative hypothesis is that the number of TV shows launched in the previous few years is NOT growing.
12.	Our second alternative hypothesis is the number of TV shows added to Netflix is higher.


