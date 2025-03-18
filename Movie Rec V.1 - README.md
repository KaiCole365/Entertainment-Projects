# Movie Recommendation System - Version 1

## Overview

This project implements a movie recommendation system using machine learning techniques. The system analyzes movie data (titles, genres, descriptions, user ratings, etc.) 
to provide personalized movie recommendations to users. This version focuses on content-based filtering, collaborative filtering using cosine similarity and TfidfVectorizer.

## Data Sources

*   **MovieLens Dataset:** Primary source for movie data and user ratings.

## Technologies Used

*   **Python:** Primary programming language.
*   **Pandas:** Data manipulation and analysis.
*   **NumPy:** Numerical computing.
*   **Matplotlib** Data visualization
*   **Seaborn** Enhanced data visualization.
*   **Scikit-learn:** Machine learning algorithms (e.g., cosine similarity, TfidfVectorizer)

## Project Structure

The project is contained within the [Movie Rec System V1.ipynb](Movie%20Rec%20System%20V1.ipynb) Jupyter Notebook. The notebook is structured as follows:

1.  **Data Loading and Preprocessing:**
    *   Loading movie data and user ratings from CSV files.
    *   Cleaning and handling missing values.
    *   Data transformation and feature engineering.

2.  **Recommendation Algorithm Implementation:**
    *   Implementing the TfidfVectorizer for the development of the recommendation system.
    *   Calculating similarity scores between movies or users via cosine_similarity. 

3.  **Recommendation Generation:**
    *   Generating movie recommendations for a given user or movie.

4.  **Evaluation:**
    *   Evaluating the performance by running several test simulations and making adjustments based on the results.

5.  **Results and Discussion:**
    *   Presenting the results of the recommendation system.
    *   Discussing the strengths and limitations of the approach.

## Key Findings

*   The system is able to provide relevant movie recommendations based on user preferences.
*   Unfortunately, the results received are static and unchanged for each movie entered into the system.
*   The system also returns duplicate movie recommendations (e.g. The Matrix returned multiple Matrix Reloaded recommendations)

## How to Run the Code

1.  **Clone the repository:**
    ```
    git clone https://github.com/KaiCole365/Entertainment-Projects.git
    cd Entertainment-Projects
    ```

2.  **Install the required libraries:**
    ```
    pip install pandas numpy scikit-learn  # Add other libraries if needed
    ```

3.  **Run the Jupyter Notebook:**
    ```
    jupyter notebook Movie\ Rec\ System\ V1.ipynb
    ```

## Potential Improvements

*   Incorporate more advanced recommendation algorithms (e.g., matrix factorization, deep learning).
*   Implement a user interface for the recommendation system.
*   Importing in random library to diversify the movie recommendation results.

## Author

### Kai Cole
