# Movie Recommendation System - Version 2

## Overview

This project implements an enhanced movie recommendation system, building upon the foundation of Version 1. The system analyzes movie data to provide personalized movie 
recommendations to users. Version 2 incorporates user interactivity and randomized recommendations, which is hypothesized to solve the static, duplicate movie recommendation results.

## Changes from Version 1:

    *   Implemented user interactivity for personalized recommendations.
    *   Incorporated randomization of recommendations for users. 
    
## Data Sources

*   **MovieLens Dataset:** Primary source for movie data and user ratings.

## Technologies Used

*  **Python**: Primary programming language.
*  **Pandas**: Data manipulation and analysis.
*  **NumPy**: Numerical computing.
*  **Matplotlib**: Data visualization
*  **Seaborn**: Enhanced data visualization.
*  **Scikit-learn**: Machine learning algorithms (e.g., cosine similarity, TfidfVectorizer)
*  **Random**: Randomization of recommendation results.

## Project Structure

The project is contained within the [Movie Rec System V2.ipynb](Movie%20Rec%20System%20V2.ipynb) Jupyter Notebook. The notebook is structured as follows:

1.  **Data Loading and Preprocessing:**
    *   Loading movie data and user ratings.
    *   Cleaning and handling missing values.
    *   Data transformation and feature engineering.

2.  **Recommendation Algorithm Implementation:**
    *   Implementing the TfidfVectorizer for the development of the recommendation system.
    *   Calculating similarity scores between movies or users via cosine_similarity
    *   **Incorporated random.shuffle to diversify movie recommendation results** (Update in Version 2)
    *   **Added function for user interactivity** (Update in Version 2)
      
3.  **Recommendation Generation:**
    *   Generating movie recommendations for a given user or movie.

4.  **Evaluation:**
    *   Evaluating the performance of the recommendation system by running several test simulations and adjusted the code based on results received.

5.  **Results and Discussion:**
    *   Presenting the results of the recommendation system.
    *   Discussing the strengths and limitations of the approach.

## Key Findings

*   The system provides more accurate and personalized recommendations compared to Version 1.
*   The hybrid approach significantly improves recommendation quality for users.
*   The most important features for generating recommendations is the addition of random.shuffle.
*   The hypothesis that random would solve for the static and duplicated movie recommendations was correct.

## How to Run the Code

1.  **Clone the repository:**
    ```
    git clone https://github.com/KaiCole365/Entertainment-Projects.git
    cd Entertainment-Projects
    ```

2.  **Install the required libraries:**
    ```
    pip install pandas numpy scikit-learn surprise # Add other libraries if needed
    ```

3.  **Run the Jupyter Notebook:**
    ```
    jupyter notebook Movie\ Rec\ System\ V2.ipynb
    ```

## Potential Improvements

*   Incorporate user feedback to improve recommendation accuracy.
*   Explore more advanced deep learning techniques.
*   Implement a real-time recommendation system using a database and API.

## Author

### Kai Cole
