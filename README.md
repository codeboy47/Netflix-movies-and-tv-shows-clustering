<p align="center"> 
  <img src="Images/netflix-logo-png-2574.png" alt="netflix-logo-png-2574.png" width="80px" height="80px">
</p>
<h1 align="center"> NETFLIX MOVIES AND TV SHOWS CLUSTERING </h1>
<h3 align="center"> AlmaBetter Verfied Project - <a href="https://www.almabetter.com/"> AlmaBetter </a> </h5>

<p align="center"> 
<img src="Images/gsmarena_001.jpg" alt="gsmarena_001.jpg" width="700px" height="382px">
</p>

<p>I have clustered similar movies and TV Shows available on Netflix taking into account of attributes like Description, Cast, Director, Genre etc of a particular movie/show.</p>

<h2> :floppy_disk: Project Files Description</h2>

<p>This Project includes a colab notebook, a data source and a presentation:</p>
<h4>Executable Files:</h4>
<ul>
  <li><b>Netflix_movies_and_tv_shows_clustering.ipynb</b> - Includes all functions required for classification operations.</li>
</ul>

<h4>Input Files:</h4>
<ul>
  <li><b>NETFLIX MOVIES AND TV SHOWS CLUSTERING.csv</b> - Input dataset having information about different shows/movies available on Netflix.</li>
</ul>

<h4>Output:</h4>
<ul>
  <li><b>Google Colab</b> - All the outputs are visible in the provided colab notebook.
</ul>

<ul>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :book: Problem Statement</h2>
Netflix is the world’s leading internet entertainment service with enjoying TV series, documentaries, and feature films across a wide variety of genres and languages. The task is to analyze the dataset from the Netflix database to cluster similar content by matching text-based features. Most of the users spend more time deciding what to watch than watching the movie or a tv show. Therefore, by understanding the existing data and analyze their trends and patterns, a machine learning models can be built for segmentation of different types of movies/tv shows that can help the user in recommending movies and shows based on their preferences.

<h2> :book: Data Summery</h2>
This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Fixable which is a third-party Netflix search engine.
In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.
Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.

* show_id : Unique ID for every Movie / Tv Show
* type : Identifier - A Movie or TV Show
* title : Title of the Movie / Tv Show 
* director : Director of the Movie
* cast : Actors involved in the movie / show
* country : Country where the movie / show was produced
* date_added : Date it was added on Netflix
* release_year : Actual Release Year of the movie / show
* rating : TV Rating of the movie / show
* duration : Total Duration - in minutes or number of seasons
* listed_in : Genere
* description: The Summary description

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

# Approach:
The full code for this article can be found here. It is implemented in Python and different clustering algorithms are used. Below is a brief description of the general approach that I employed:
* Data cleaning and pre-processing: 
Here I checked and dealt with missing and duplicate variables from the data set as these can grossly affect the performance of different machine learning algorithms (many algorithms do not tolerate missing data).
* Exploratory Data Analysis: 
Here I wanted to gain important statistical insights from the data and the things that I checked for were the distributions of the different attributes, correlations of the attributes with each other and the target variable and I calculated important odds and proportions for the categorical attributes.
* Clustering:
Clustering or cluster analysis is a machine learning technique, which groups the unlabelled dataset. It can be defined as "A way of grouping the data points into different clusters, consisting of similar data points. The objects with the possible similarities remain in a group that has less or no similarities with another group."
It does it by finding some similar patterns in the unlabelled dataset such as shape, size, colour, behaviour, etc., and divides them as per the presence and absence of those similar patterns. 
It is an unsupervised learning method; hence no supervision is provided to the algorithm, and it deals with the unlabeled dataset. After applying this clustering technique, each cluster or group is provided with a cluster-ID. ML systems can use this id to simplify the processing of large and complex datasets.

# Data insights:
* Most of the content available on Netflix is for mature audiences which shows the demand for kids’ content is low.
* In recent years, Netflix has increasingly focused on TV shows rather than movies.
* Most movies/TV shows available on Netflix were directed by Raúl Campos and Jan Suter.
* Based on the content available on Netflix, the United States has produced the highest number of movies and TV shows.
* Most movies’ duration is around 80 to 120 minutes whereas the duration for TV shows is around 1 to 2 seasons.
* Japan has more TV shows than movies on Netflix.
* Anupam Kher has acted in most of the movies and shows present on Netflix.
* Hierarchical clustering formed 4 clusters whereas K-means formed 5 clusters.
* We get the optimal value of k at 5 using the elbow method and Silhouette score.
* Content is divided into 5 clusters: Family movies, Documentaries, International TV Shows, International movies and Kids’ TV shows.


# Conclusion
In conclusion, tailored recommendations can be made based on information about movies and TV shows. In addition, similar models can be developed to provide valuable recommendations to consumers in other domains.
It will solve for improved movie and TV-Show selection times with a considerable growth in satisfaction of the content being consumed leading to more user engagement and greater trust in Netflix recommendations.


[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/akshit101/)

