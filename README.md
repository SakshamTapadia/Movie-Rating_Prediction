# Movie Rating Prediction

## Project Overview

This project aims to develop a model to predict movie ratings based on various features such as movie details, user demographics, and past ratings. The dataset comprises three files: movies, ratings, and users. By combining these datasets and applying machine learning techniques, we can build a predictive model for movie ratings.

## Datasets

The datasets used in this project can be found at the following links:

- [Movies Dataset](https://github.com/SakshamTapadia/CODSOFT/blob/main/Task2%20-%20DataSet%20Movies.csv)
- [Ratings Dataset](https://github.com/SakshamTapadia/CODSOFT/blob/main/Task2%20-%20DataSet%20Ratings.csv)
- [Users Dataset](https://github.com/SakshamTapadia/CODSOFT/blob/main/Task2%20-%20DataSet%20Users.csv)

### Movies Dataset

- **MovieID**: Unique ID for each movie
- **Title**: Title of the movie
- **Genres**: Genres associated with the movie

### Ratings Dataset

- **UserID**: Unique ID for each user
- **MovieID**: Unique ID for each movie
- **Rating**: Rating given by the user (1-5)
- **Timestamp**: Time of rating

### Users Dataset

- **UserID**: Unique ID for each user
- **Gender**: Gender of the user
- **Age**: Age of the user
- **Occupation**: Occupation of the user
- **Zip-code**: Zip code of the user

## Project Notebook

The complete project notebook is available [here](https://github.com/SakshamTapadia/CODSOFT/blob/7432e5358547ca78e1e5f04beb9bcb77e8aef289/Task2%20-Movie%20Rating%20Prediction%20using%20Python.ipynb). It includes the following steps:

1. **Data Exploration and Preprocessing**:
    - Load and inspect the datasets.
    - Merge the datasets on common keys (UserID and MovieID).
    - Handle missing values.
    - Encode categorical variables.
    - Feature engineering.

2. **Exploratory Data Analysis (EDA)**:
    - Visualize the distribution of features.
    - Analyze the correlation between features and ratings.

3. **Model Building**:
    - Split the data into training and testing sets.
    - Train multiple machine learning models (e.g., Linear Regression, Decision Tree, Random Forest, SVD).
    - Evaluate model performance using metrics such as RMSE and MAE.

4. **Model Evaluation and Selection**:
    - Compare the performance of different models.
    - Select the best model based on evaluation metrics.

5. **Prediction and Conclusion**:
    - Make predictions on the test set.
    - Summarize the findings and conclusion.

## Results

The results of the model evaluation and the final predictions on the test set are included in the project notebook. The best performing model achieved a high accuracy and provided insights into the most important features influencing movie ratings.

## Conclusion

This project demonstrates the application of machine learning techniques to predict movie ratings based on a combination of movie details, user demographics, and past ratings. By leveraging data preprocessing, exploratory data analysis, and model evaluation, we can gain valuable insights and build accurate predictive models.
