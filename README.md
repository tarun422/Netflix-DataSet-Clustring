# Netflix-DataSet-Clustring

![acastro_211025_1777_netflix_0001](https://github.com/tarun422/Netflix-DataSet-Clustring/assets/81609862/2f43079d-615d-4be7-874f-57a69df525ae)

**This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.
In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.
Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.**

# Dataset Information
* Number of instances: 7787
* Number of attributes: 12

# Features information:
1. **show_id** : Unique ID for every Movie / Tv Show
2. **type** : Identifier - A Movie or TV Show
3. **title** : Title of the Movie / Tv Show
4. **director** : Director of the Movie
5. **cast** : Actors involved in the movie / show
6. **country** : Country where the movie / show was produced
7. **date_added** : Date it was added on Netflix
8. **release_year** : Actual Releaseyear of the movie / show
9. **rating** : TV Rating of the movie / show
10. **duration** : Total Duration - in minutes or number of seasons
11. **listed_in** : Genere
12. **description** : The Summary description

# Prerequisites
* Understanding of Python and its libraries like Numpy, pandas, Matplotlib and seaborn

# Technologies used

* IDE- Google colab

**Goal:- The main goal is to make a TV shows and Movies recomandaction system**

# Project Work flow

1. Importing Libraries

2. Loading the Dataset

3. Data Cleaning

4. Handling Outliers

5. Data Visualization
6. Making clusters

7. Conclusion

# Conclusion

* This Netflix Dataset is a Unsupervised machine leaning dataset

* Data set contains 7787 rows and 12 columns

* Director features contains large number of missing values (more then 30%) so we decided to drop this director attribute.

* We have two types of content TV shows and Movies (30.86% contains TV shows and 69.14% contains Movies

* The growth rate of the contanton netflix is exponential

* Mostly movies are for adults sections

* US and India produse more than 70% of the content

* By analysing the content added over years we get to know that in recent years netflix is focusing movies than TV shows (movies is increased by 80% and TV shows is increased by 73% compare to 2016 data)

* By applying the silhouette score method for n range clusters on dataset we got best score which is 0.356 for clusters = 3, it means content explained well on their own clusters.

* Speaking about other different cluster methods, K mean, hierarchical, agglomerative clustering on data, we got the best cluster arrangements.

* 3 is the best cluster for this dataset

![55773758016451](https://github.com/tarun422/Netflix-DataSet-Clustring/assets/81609862/56f2f514-3018-4bd6-8699-c8b56ff1aac3)

