# ReelGood Movie and TV Show Recommender System
This repository contains a Jupyter Notebook that implements a movie and TV show recommender system using ReelGood data. The recommender system allows users to input their favorite movie titles, genres, or a description of the types of movies and shows they like. Based on this input, the system suggests similar movies or shows.

## Features
Title-based recommendations: Recommend movies or shows similar to a given title.
Genre-based recommendations: Recommend top-rated movies or shows within a specified genre.
Tag-based recommendations: Recommend top-rated movies or shows based on user-specified tags.

## Getting Started
### Prerequisites
Ensure you have the following Python libraries installed:

- pandas
- numpy
- seaborn
- re

### Installation
1. Clone the repository:

git clone https://github.com/your-username/reelgood-recommender-system.git

2. Upload the repository to Google Colab or open the Jupyter Notebook locally.
### Data
The data used in this notebook is from ReelGood, which includes detailed information about movies and TV shows such as genre, ratings, and more.

### Usage
Load the data: Ensure that the ReelGood data CSV file is available and correctly loaded in the notebook.\
Run the cells: Execute the cells in the notebook to perform data cleaning and preprocessing.\
Input preferences: Provide your movie or show preferences as inputs in the specified format.\
Get recommendations: The system will output recommended movies or shows based on the input.
### Example (Please refer to [DSO_574_Bonus.ipynb](https://github.com/Jecoc907/Movie_Recommender_System/blob/main/DSO_574_Bonus.ipynb) )
### Notebook Contents
Data Cleaning / Preprocessing: Steps to clean and prepare the data for analysis.\
Recommender System:\
Version 1: Check if the movie/TV show exists in the database.\
Version 2: Return the top 3 IMDB rated movies/TV shows under the same genre.\
Version 3: Return the top 3 movies/TV shows under a given genre when a genre is provided as input.
Version 4: Return the top 3 movies/TV shows under a given tag when a tag is provided as input.
Final Version: Users can input either a [Movie/Genre/Tag] to get 3 [movie/TV show] recommendations.

### License
This project is licensed under the MIT License.

