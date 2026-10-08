# Book Recommendation Engine using KNN

A machine learning project that recommends books based on user ratings and similarities between books using the **K-Nearest Neighbors (KNN)** algorithm.

This project was completed as part of the **freeCodeCamp Machine Learning with Python** curriculum.

## Project Overview

The recommendation system analyzes book ratings from users and finds books that are similar to a selected book.

The **K-Nearest Neighbors** algorithm is used to identify books with similar rating patterns and generate recommendations.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn

## Machine Learning Algorithm

The project uses the **K-Nearest Neighbors (KNN)** algorithm.

The system:

1. Loads book and user rating data.
2. Cleans and filters the dataset.
3. Creates a book-user rating matrix.
4. Calculates similarities between books.
5. Finds the nearest books using KNN.
6. Returns book recommendations.

## Dataset

The project uses book information and user-rating data provided as part of the freeCodeCamp challenge.

The dataset contains information about:

- Books
- Users
- Ratings
- Book titles
- Authors

## Recommendation Function

The project includes a recommendation function that accepts a book title and returns similar books with their similarity distances.

Example:

```python
get_recommends("Where the Heart Is (Oprah's Book Club)")
```

The function returns the selected book along with a list of recommended books.

## Project Structure

```text
book-recommendation-engine/
├── book_recommendation.ipynb
├── requirements.txt
└── README.md
```

## How to Run

Install the required libraries:

```bash
pip install -r requirements.txt
```

Then open the Jupyter Notebook:

```bash
jupyter notebook
```

Run the notebook cells to load the dataset, train the KNN model, and generate book recommendations.

## Result

The project successfully passed the **freeCodeCamp Book Recommendation Engine using KNN** challenge.
