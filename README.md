# Movie Recommender System

This project builds a **content-based movie recommender system** using metadata from the TMDB 5000 movies dataset. It leverages information like movie genres, keywords, and tags to recommend movies that are similar to a selected title.

## Features
- **Data Source**: The dataset includes two files: `tmdb_5000_credits.csv` and `tmdb_5000_movies.csv`.
- **Preprocessing**: The system extracts relevant features like genres, keywords, and movie overviews, which are cleaned and prepared for use in a recommendation model.
- **Content-based Recommendation**: The system suggests movies based on the content (tags, genres, and keywords) of movies. 
- **Similarity Calculation**: The similarity between movies is calculated using vectorized feature representations.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/movie-recommender-system.git
   cd movie-recommender-system ```

Install the required Python packages:
```
pip install -r requirements.txt
```

# Data
tmdb_5000_movies.csv: Contains movie metadata such as budget, genres, original language, popularity, and vote counts.
tmdb_5000_credits.csv: Contains detailed information about the cast and crew of each movie.
# Dependencies
1.pandas
2.numpy
3.scikit-learn
4.nltk
# Example usage
```
recommendations = recommend_movies('Avatar')
print(recommendations)
```
