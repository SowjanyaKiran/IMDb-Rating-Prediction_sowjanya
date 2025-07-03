#IMDb Rating Prediction Using Machine Learning#
This repository contains a Machine Learning project that aims to predict the IMDb ratings of TV shows based on features such as title, genre, year of release, and number of votes. The project involves data preprocessing, visualization, feature engineering, model training, evaluation, and prediction using the IMDb Top 250 dataset.

#Contents#
Dataset: Contains details like show title, genre, release year, IMDb votes, ratings, director, and more.
Preprocessing: Data cleaning, handling missing values, encoding categorical variables (e.g., Genre).
Visualization: Statistical charts and plots showing trends in ratings, votes, genres, and more.
Modeling: Various regression models applied to predict IMDb ratings.
Evaluation: Analysis using MAE, MSE, and R² to select the best model.
Prediction: Generating rating predictions for unseen data and comparing them with actual values.

#Project Objective#
To build a predictive model using machine learning techniques that can accurately estimate the IMDb rating of a show or movie based on features like:
Genre(s)
Year of Release
Number of IMDb Votes
Other show metadata

#Features of the Dataset#
Title: Name of the TV show/movie.
Year: Year of release.
Genre: One or more genres associated with the title (Drama, Action, etc.).
IMDb Votes: Total number of audience votes.
IMDb Rating: Target variable (out of 10).
Director & Writer Info: Used for exploration.
Duration, Certificate: Used optionally for feature correlation.

#Technologies Used#
Python – Primary programming language.
Pandas – Data manipulation and preprocessing.
NumPy – Mathematical operations.
Matplotlib & Seaborn – Visualizations and data plots.
Scikit-learn – Model building, evaluation, and hyperparameter tuning.
Jupyter Notebook – Interactive analysis and experimentation.

#📊 Key Analysis & Visualizations#
🔍 Rating Distribution: Understanding how ratings are spread across the dataset.
📈 Votes vs Ratings: Scatter plots showing correlation between popularity and rating.
🧠 Correlation Heatmaps: Numeric correlation between features.
📊 Genre-wise Rating Analysis: Average ratings grouped by genre.
📅 Yearly Trends: Ratings and votes by release decade.

#Modeling Approach#
Preprocessing: One-hot encoding for genres, scaling for numeric fields (votes).
Train-Test Split: 80/20 for model validation.
Models Tried:
Linear Regression
Random Forest Regressor
Decision Tree Regressor
CatBoost Regressor
Evaluation Metrics:
MAE (Mean Absolute Error)
MSE (Mean Squared Error)
R² Score (Coefficient of Determination)

#Hyperparameter Tuning#
Used GridSearchCV and RandomizedSearchCV to optimize model performance.
Tuned parameters like:
n_estimators
max_depth
learning_rate (for boosting models)

#Final Model & Predictions#
Best-performing model selected based on evaluation metrics.
Used to predict ratings on unseen test data.
Predicted vs Actual ratings plotted on a scatter plot for validation.

#📈 Results & Interpretation#
Identified most influential features (e.g., Votes, Genre).
Visualized residuals to check for overfitting/underfitting.
