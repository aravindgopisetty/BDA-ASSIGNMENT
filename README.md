# BDA-ASSIGNMENT
# Movie Recommendation System using PySpark and ALS

This Colab notebook demonstrates building a movie recommendation system using PySpark and Alternating Least Squares (ALS) algorithm.

## Overview

The notebook covers the following steps:

1. **Setting up Spark:** Installing Java, Spark, and findspark.
2. **Loading Data:** Downloading and loading the MovieLens dataset.
3. **Data Exploration:** Examining the movies and ratings data.
4. **Model Training:** Building and training an ALS model.
5. **Evaluation:** Evaluating the model's performance using RMSE.
6. **Generating Recommendations:** Recommending movies for users and items.

## Dataset

The notebook uses the MovieLens dataset, a popular benchmark dataset for recommendation systems. It contains movie ratings provided by users.

## Algorithm

The recommendation system is based on the Alternating Least Squares (ALS) algorithm, a collaborative filtering approach that learns latent factors from user-item interactions to predict ratings and generate recommendations.

## Usage

1. Open this notebook in Google Colab.
2. Run all the cells in sequential order.
3. Explore the code and modify it to experiment with different parameters or datasets.

## Requirements

- Google Colab environment
- Python 3
- PySpark
- MovieLens dataset

## Results

The notebook provides the following results:

- RMSE score for evaluating the model's performance.
- Top 10 movie recommendations for a specific user.
- Top 10 user recommendations for a specific movie.

## Note

- The notebook assumes that you have a basic understanding of Python, PySpark, and recommendation systems.
- You can adjust the hyperparameters of the ALS model to fine-tune its performance.
- The MovieLens dataset is downloaded automatically in the notebook.

## License

This project is licensed under the MIT License.
