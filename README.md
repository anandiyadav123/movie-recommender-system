# Movie-recommender-system
A content-based movie recommendation system that suggests movies to users based on similarity in features like genres, keywords, cast, and crew using the TMDB dataset.

# Project Overview
This project leverages movie metadata to build a recommendation engine that suggests similar movies based on user input. It uses feature engineering and machine learning techniques such as:

Data Cleaning and Preprocessing
//Feature Extraction (Genres, Cast, Keywords, Director)
//Vectorization using CountVectorizer / TF-IDF
//Similarity calculation using Cosine Similarity

# Key Features
Content-Based Filtering: Uses movie attributes rather than user behavior.
Text Feature Engineering: Combines multiple metadata fields into a single tag for vectorization.
Similarity Calculation: Uses Cosine Similarity on vectorized tags to find top matches.
Clean, Modular Code: Easily extensible and readable codebase using pandas, scikit-learn, etc.
 
# Dataset Used
TMDB 5000 Movie Dataset
Contains metadata of over 5,000 movies, including:
Titles
Genres
Overview and Taglines
Cast, Crew, and Keywords

📎 Dataset on Kaggle

# Tech Stack
Python
Pandas & NumPy – data preprocessing
Scikit-learn – vectorization and similarity analysis
CountVectorizer 

# How It Works
Preprocesses movie metadata and combines key fields into a unified "tag".
Vectorizes the text using CountVectorizer 
Computes cosine similarity between movies.
Returns top 5 similar movies for any input title.






