# Movie Rating Prediction

This project predicts the rating of a movie based on features like genre, director, actors, number of votes, and release year using machine learning techniques.

## Project Overview

The objective is to analyze historical movie data and train a regression model that can accurately estimate movie ratings given by users or critics.

## Features Used

- Genre  
- Director  
- Actor 1  
- Actor 2  
- Number of Votes  
- Release Year  

## Machine Learning Approach

- Model: Random Forest Regressor  
- Evaluation Metrics:
  - Root Mean Squared Error (RMSE)
  - R² Score

## Model Performance

- RMSE: 1.125  
- R² Score: 0.337  

These results indicate moderate predictive performance. Further tuning and feature engineering can help improve the model.

## Sample Predictions

| Actual Rating | Predicted Rating |
|---------------|------------------|
| 8.2           | 7.83             |
| 2.6           | 5.18             |
| 5.3           | 4.80             |
| 3.2           | 6.48             |
| 5.2           | 4.66             |

## Technologies Used

- Python  
- pandas  
- scikit-learn  
- numpy  

## Steps

1. Load and clean the dataset  
2. Encode categorical variables  
3. Train the regression model  
4. Evaluate the model performance  
5. Make predictions on test data  

## Author

Sangamithra Ravi

