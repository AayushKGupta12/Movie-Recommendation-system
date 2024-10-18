# Movie Recommendation System
## Project Overview

This project implements a **Movie Recommendation System** that makes recommendations to users on movies based on attributes such as genre, keywords, cast, and crew. A recommendation system has been developed using Python in which the Pandas library is used in dealing with and processing the movie dataset.
## Features

Clean and preprocess the movie dataset.
Develop a recommendation system based on content filtering, where movie titles are matched against user inputs.
Multiple features used in calculating the similarities of movies include genres, keywords, cast, and crew.
## Dataset
The dataset that has been adopted for the project include:
- **Movies Metadata**: Movie title, overview, genres, keywords, cast, and crew.
- **Ratings Data**: User ratings of different movies.
## Libraries Used
- **Python**: Core language.
- **Pandas**: Data manipulation and analysis.
- **Numpy**: Numerical computations.
- **Scikit-learn**: To apply machine learning algorithms, for instance, cosine similarity.
- **NLTK**: Used to bring about natural language processing, such as tokenization.

## Running the Project
1. Clone the repository:
```bash
git clone <repository-link>
```
2. Install all required libraries
```bash
pip install -r requirements.txt
```
3. Run the notebook:
Open `Movie_Recommendation_System.ipynb` in Jupyter Notebook and execute all the cells.
## How It Works

1. Data Preprocessing: The null values from the dataset are removed and all the features with redundancy are stripped away.
2. Feature Extraction: Features such as genres, keywords, cast, and crew are allowed to flow into one-dimensional vectors
3. Content-Based Filtering: Cosine similarities are used between the movies. Thus, in regard to that, it gives the recommendations of movies
## Sample Use Case

It will suggest movies that are similar to input of the user in the movie name, based on genres, cast, and keywords.
## Future Improvements
This is an attempt which can be used to make people-based recommendations using collaborative filtering.
Deep learning methods can also be employed to do very accurate predictions.
## Acknowledgements
This project was developed under the data science and machine learning learning track, using publicly available datasets from some sources like The Movie Database (TMDb).
