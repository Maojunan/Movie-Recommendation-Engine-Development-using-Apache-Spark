# Movie Recommendation System with Spark and ALS

This project implements a personalized movie recommendation system using **Apache Spark** and the **Alternating Least Squares (ALS)** algorithm. Leveraging collaborative filtering techniques, the system predicts user ratings and recommends movies based on the MovieLens dataset.

## Features
- **Data ETL Pipeline**: Efficient data extraction, transformation, and loading of MovieLens dataset (movies, ratings, links, tags) into Spark DataFrames.
- **ALS Model**: Uses Spark MLlib's ALS algorithm for collaborative filtering to find latent patterns in user and movie features.
- **Hyperparameter Tuning**: Grid search over model parameters such as rank, regularization, and max iterations for optimal performance.
- **Evaluation & Metrics**: Model accuracy evaluated with Root Mean Square Error (RMSE), achieving an RMSE of approximately 0.88 on the test set.
- **Recommendations & Similarity**: Provides movie recommendations for specific users and finds similar movies based on ALS-generated feature vectors.

## Results
The final model provides effective, personalized recommendations with high accuracy, demonstrating the power of Spark's ALS in building scalable recommendation systems.
