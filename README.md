# NETFLIX Movie Recommendation Project

This repository contains a Netflix-inspired movie recommendation project built as a Jupyter Notebook. The goal is to recommend movies based on content similarity and engagement signals such as ratings and movie metadata.

## Project Overview

The notebook analyzes the TMDB movie dataset and builds a recommendation system that considers:

- Movie genres
- Overview/description text
- Crew information (directors, actors)
- User ratings and popularity
- Similarity-based recommendation using TF-IDF and cosine similarity

The project applies techniques such as:

- Data cleaning and exploratory data analysis (EDA)
- Text vectorization with TF-IDF
- Dimensionality reduction using SVD
- Cosine similarity matching
- Collaborative filtering-inspired rating considerations

## Features

- Movie dataset exploration and preprocessing
- Content-based movie recommendations
- Movie metadata analysis
- Similarity-based recommendation logic
- Jupyter Notebook workflow for experimentation and results review

## Dataset

The project uses movie data from TMDB, including files such as:

- `tmdb_5000_movies.csv`
- `tmdb_5000_credits.csv`

These datasets contain information about movies, cast, crew, genres, ratings, descriptions, and related metadata.

## Tech Stack

- Python
- Pandas
- NumPy
- Jupyter Notebook
- scikit-learn
- TF-IDF vectorization
- Truncated SVD
- Cosine similarity

## Repository Structure

```text
NETFLIX/
├── Code.ipynb          # Main notebook with project logic
├── README.md           # Project documentation
└── ...                 # Dataset files or supporting assets (if added later)
```

## How to Run

1. Open the notebook in Jupyter or Google Colab.
2. Ensure required Python libraries are installed:

```bash
pip install pandas numpy scikit-learn
```

3. Run the cells in order to:
   - load the datasets
   - preprocess the data
   - build the recommendation model
   - generate movie suggestions

## Example Use Case

The system can recommend movies similar to a selected title by comparing:

- genre overlap
- textual similarity in plot/overview
- cast and crew similarity
- rating trends

## Notes

This project is intended as a learning and demonstration notebook for recommendation systems and content-based filtering in a Netflix-like domain.

## License

This repository does not currently include a license file. If you plan to share or distribute the project publicly, it is recommended to add an appropriate open-source license.
