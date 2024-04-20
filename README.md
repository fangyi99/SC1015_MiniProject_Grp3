# Movie Popularity Prediction

## Overview
This is a Mini-Project for the course of SC1015 Introduction to Data Science and Artificial Intelligence which analyzes movies from The Movies Dataset. Our aim is to predict the popularity of movies based on their features using machine learning techniques.

## Table of Contents:
- Import Libraries
- Data Analysis
- Data Cleaning
- Data Preparation & Visualization
- Machine Learning
    - Pre-Model Fitting
    - Model Building
    - Model Comparison
    - Post-Model Outlier Removal
    - Feature Importance
- Conclusion


## Problem Statement
- Which model would be the best to accurately forecast the popularity of movies based on a range of variables?
- Which feature has the most importance in affecting the movie popularity?
 

## Models Used
- Multiple Linear Regression
- Random Forest Regression
- Gradient Boosting Regression

## Conclusion
- Removing outliers can increase the accuracy of a model. 
- Gradient Boosting Regression is the best model across the three models used in predicting movie popularity. 
- Vote_count has the highest correlation with movie popularity. 
- Runtime of a movie can affect audience engagement and interest.
- Large budget does not guarantee high popularity and vice versa.
- The top 5 genres most capable of predicting popularity, in descending order, are Mystery, Fantasy, War, Science Fiction, and Music.


## What did we learn from this project?
- Extraction of data from a list of dictionary into a list of string
- Normalization and scaling of data
- Interpretation of visualization plots using Multiple Linear Regression
- One-hot encoding to convert data into numerical data
- Implementation of Multiple Linear Regression, Random Forest Regressor and Gradient Boosting Regressor
- Feature Engineering

## Contributions
<table>
  <tr>
    <td></td>
    <td colspan=3; align="center">Contributors</td>
  </tr>
  <tr>
    <td>Contents</td>
    <td>Fang Yi (@fangyi99)</td>
    <td>Joey (@joeyleonggg)</td>
    <td>Yi Hsuen (@yiihsuenn)</td>
  </tr>
  <tr>
  <td>Data Preparation</td>
  <td>Convert Datatype</td>
  <td>Remove duplicates<br><br>Remove null values</td>
  <td>Extract data from list of dictionary into list of strings<br><br>Normalization and Scaling<br><br>Removal of outliers</td>
  </tr>
  <tr>
    <td>Data Visualization</td>
    <td>Relation between popularity with other independent variables<br>(scatter plot)<br><br>Feature Importance<br>(box plot)</td>
    <td>Genre distribution<br>(bar plot)<br><br>Rating distribution<br>(box plot and violin plot)</td>
    <td>Relation between each pair of variables<br>(pair plot)<br><br>Correlation<br>(heatmap)</td>
  </tr>
  <tr>
    <td>Model Building</td>
    <td>Gradient Boosting Regression</td>
    <td>Random Forest Regression </td>
    <td>Multiple Linear Regression</td>
  </tr>
  <tr>
    <td>Feature Engineering</td>
    <td>-</td>
    <td>-</td>
    <td>One Hot Encoding</td>
  </tr>
</table>

## References
- https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset
- https://corporatefinanceinstitute.com/resources/data-science/multiple-linear-regression/
- https://scikit-learn.org/stable/auto_examples/ensemble/plot_gradient_boosting_regression.html

