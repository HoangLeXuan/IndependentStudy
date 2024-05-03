# Modeling the Demographic of Immigrant Human Capital in 2021 

This repository contains all the datasets, code files, results, graphs, plots, and tables for our study on employment and unemployment rates across various demographic groups. We utilized the 2021 National Survey of College Graduates (NSCG) dataset, focusing on factors such as age, gender, race, education levels, parental education, job preferences, and citizenship status.

## Objective

Our study aims to identify key predictive variables and compare the accuracy of various statistical and machine learning models in interpreting labor market dynamics.

## Models Used

- Multivariate Logit Model
- Deep Learning Logit Model
- Probit Model
- Random Forest Model
- K-nearest Neighbors (K-n) Model

Each model is tailored with a subset of variables to enhance prediction accuracy while addressing statistical issues like multicollinearity and overfitting.

## Repository Structure

- `data/` - Contains all datasets used in this study.
- `code/` - Contains all scripts and code files for running the statistical and machine learning models. The results are included in the Rmd files of the code.

## Installation

To run the scripts, clone this repository and install the required packages:
google.colab
pandas
numpy
sklearn.model_selection
sklearn.preprocessing
sklearn.compose
sklearn.pipeline
sklearn.neighbors
sklearn.metrics
matplotlib.pyplot
seaborn
sklearn.feature_selection

```bash
git clone https://github.com/kahf10/IndependentStudy.git
