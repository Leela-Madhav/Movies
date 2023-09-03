# Movie Recommendation System

## Overview

This project implements a movie recommendation system that suggests movies to users based on their favorite movie's name. It leverages a dataset of movies and various movie attributes to calculate movie similarities using TF-IDF (Term Frequency-Inverse Document Frequency) and cosine similarity techniques.

## Key Features

- Data Loading: Loads movie data from a CSV file into a Pandas DataFrame.
- Data Exploration: Displays basic information about the dataset, such as the first and last rows, shape, and size.
- Feature Selection and Data Preprocessing: Selects relevant movie attributes and fills missing values with empty strings.
- Feature Combination: Combines selected features into a single column for text-based analysis.
- Text Vectorization: Uses a TF-IDF vectorizer to convert textual descriptions into TF-IDF feature vectors.
- Cosine Similarity Calculation: Computes cosine similarity between movies to determine their similarity.
- User Input: Prompts the user to enter their favorite movie's name.
- Movie Matching: Finds the closest match in the dataset to the user's input, accounting for minor spelling or naming variations.
- Recommendation Generation: Generates movie recommendations based on the user's input and similarity scores.
- Display Recommendations: Presents a list of top recommended movies to the user.

## How to Use

1. **Environment Setup:** Ensure you have Python installed along with the necessary libraries mentioned in the project code, such as Pandas, NumPy, Scikit-learn, and difflib.

2. **Data Preparation:** Prepare your movie dataset in a CSV file named `movies.csv`. Make sure it includes columns for movie titles, genres, keywords, taglines, cast, and directors.

3. **Run the Code:** Execute the project code using a Python environment. The code will load the dataset, perform text processing, and prompt you to enter your favorite movie's name.

4. **Receive Recommendations:** Based on your input, the system will recommend a list of movies similar to your favorite.

## Author

- Leela Madhav
- leelamadhav20@gmail.com

## License

This project is licensed under the [License Name] License - see the [LICENSE.md](LICENSE.md) file for details.

