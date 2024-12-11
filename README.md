# Final-Project
# Spotify Song Streams Prediction
## Project Overview

This project aims to predict the number of streams a song will receive using machine learning models. The dataset includes features such as song attributes (e.g., BPM, danceability, energy), artist-related data, and playlist/chart placements. By leveraging advanced preprocessing techniques and multiple machine learning algorithms, this project identifies the best-performing model for accurate stream prediction.
The repository contains all necessary code and documentation to reproduce the results, including exploratory data analysis (EDA), feature engineering, model training, hyperparameter optimization, and evaluation.

### Features
#### Dataset: The dataset includes numeric and categorical features such as:
#### Numeric: bpm, danceability_%, valence_%, energy_%, acousticness_%, etc.
#### Categorical: track_name, mode, key, artist(s)_name.
#### Models Implemented:
Ridge Regression
Random Forest Regressor
Support Vector Regressor (SVR)
K-Nearest Neighbors Regressor (KNN)
Deep Learning Model (TensorFlow/Keras)
#### Advanced Techniques:
Feature preprocessing using pipelines.
Dimensionality reduction with Principal Component Analysis (PCA).
SHAP (SHapley Additive exPlanations) for feature importance analysis.
Cluster analysis to identify patterns in song attributes.
Hyperparameter optimization using GridSearchCV and Random Search.

### Files
#### .png files are relevant plots
#### draft.ipynb is all model constructions and results
#### eda.ipynb contains all EDA
