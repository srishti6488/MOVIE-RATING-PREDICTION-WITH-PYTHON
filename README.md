# Movie Rating Prediction

## Project Overview

The goal of this project is to build a model that predicts the rating of a movie based on various features such as genre, director, and actors. This involves analyzing historical movie data and developing a regression model to estimate the rating given to a movie by users or critics.

## Objectives

1. **Data Analysis**: Investigate the dataset to understand its structure, identify patterns, and uncover insights related to movie ratings.
2. **Preprocessing**: Clean and prepare the data for modeling. This involves handling missing values, converting data types, and formatting features.
3. **Feature Engineering**: Transform raw data into meaningful features that can improve model performance.
4. **Model Building**: Use regression techniques to build a predictive model for movie ratings.
5. **Evaluation**: Assess the performance of the model using metrics such as mean squared error, mean absolute error, and R-squared score.

## Dataset

The dataset includes the following features:

- **Name**: Title of the movie.
- **Year**: Release year of the movie.
- **Duration**: Duration of the movie.
- **Genre**: Genre(s) of the movie.
- **Rating**: Rating given to the movie.
- **Votes**: Number of votes received for the movie.
- **Director**: Director of the movie.
- **Actor 1, Actor 2, Actor 3**: Lead actors in the movie.

## Data Cleaning and Preprocessing

### Handling Missing Values

- Remove rows with missing ratings and other essential information like genre, director, and actors.

### Data Transformation

- **Votes**: Convert vote counts from string to integer and remove commas.
- **Year**: Extract the year from the format (e.g., (2019)).
- **Duration**: Remove 'min' from the duration and handle missing values.

### Feature Encoding

- Convert categorical features like genre, director, and actors into numerical values using techniques like label encoding or one-hot encoding.

## Exploratory Data Analysis (EDA)

1. **Top Movies by Rating**: Identify and analyze movies with the highest ratings.
2. **Genre Distribution**: Explore the distribution of movie genres and their popularity.
3. **Directors by Average Rating**: Investigate which directors have the highest average ratings.
4. **Votes vs. Rating**: Examine the relationship between the number of votes and movie ratings.
5. **Actors' Popularity**: Analyze the number of movies featuring top actors.
6. **Movies Released Over the Years**: Study trends in the number of movies released each year.
7. **Movies with High Ratings and Votes**: Filter movies that have high ratings and a large number of votes.

## Feature Engineering

1. **Feature Extraction**: Derive new features from existing ones to capture more information. For example, extracting features from the 'Genre' column.
2. **Encoding Categorical Features**: Convert categorical features like genres and directors into numerical values suitable for machine learning models.

## Model Building

1. **Model Selection**: Choose appropriate regression models such as Linear Regression and Decision Tree Regression.
2. **Training**: Train the model using the prepared dataset.
3. **Evaluation**: Assess the model's performance using evaluation metrics to ensure it accurately predicts movie ratings.

## Conclusion

The Movie Rating Prediction project provides insights into how various factors such as genre, director, and actors influence movie ratings. By building and evaluating a regression model, you can estimate the ratings of movies based on historical data, helping in understanding rating trends and making informed decisions in the film industry.

 
