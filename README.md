# Project Name : Bike Sharing Prediction

> A Multiple Linear Regression Model to predict the demand for shared bikes in the American market.

## Table of Contents

- [General Info](#general-information)
- [Objective](#objective)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)

## General Information

BoomBikes, a bike-sharing provider in the United States, has faced significant revenue declines due to the COVID-19 pandemic. To prepare for the post-pandemic recovery, BoomBikes aims to understand the factors affecting the demand for shared bikes and develop a business strategy to maximize profits. This project involves building a Multiple Linear Regression model to predict the demand for shared bikes using various independent variables.

The dataset used in this project contains daily bike rental counts and several factors that might influence bike demand, including weather conditions, seasonal effects, and user types (casual or registered).

## Objective

The objective of this project is to build a predictive model using Multiple Linear Regression to forecast the demand for shared bikes in the American market. The model aims to identify and quantify the significant factors influencing bike demand, enabling BoomBikes to develop strategic business decisions and enhance revenue post-COVID-19.

## Contents

1. [Problem Statement](#problem)
2. [Goal](#goal)
3. [Data Reading and Understanding](#data-steps)
   - [Import Required Libraries and Configure Default Settings](#import-required-libraries-and-configure-default-settings)
   - [Read the dataset and understand](#read-the-dataset-and-understand)
4. [Data Cleaning and Manipulation](#data-cleaning-and-manipulation)
   - [Drop Columns that are not Useful for this Analysis](#drop-columns-that-are-not-useful-for-this-analysis)
   - [Check Outliers](#check-outliers)
   - [Convert values to Categorial Types](#convert-values-to-categorial-types)
   - [Create Dummy Variables](#create-dummy-variables)
5. [Exploratory Data Analysis (EDA)](#eda)
   - [Visualising Numeric Variables](#univariate-analysis)
   - [Visualising Categorial Variables](#bivariate-analysis)
   - [Correlation Matrix](#correlation-matrix)
6. [Model Building](#model-building)
   - [Train-Test Split](#train-test-split)
   - [Rescaling the data](#rescaling)
   - [Automated Approach - Recursive Feature Elimination (RFE)](#automated-approach-recursive-feature-elimination-rfe)
   - [Manual Elimination](#manual-elimination)
     - [Manual 1](#model-1)
     - [Manual 2](#model-2)
     - [Manual 3](#model-3)
     - [Manual 4](#model-4)
     - [Manual 5](#model-5)
     - [Manual 6](#model-6)
     - [Manual 7](#model-7)
7. [Model Interpretation](#model-interpretation)
   - [Hypothesis Testing](#hypothesis-testing)
   - [F Statistics](#f-statistics)
   - [Equation](#equation)
8. [Model Evaluation](#model-evaluation)
   - [Residual Analysis](#residual-analysis)
   - [Linearity Check](#linearity-check)
   - [Predictions and Evaluation](#predictions-and-evaluation)
   - [R-Squared value on Test Set](#r-squared-value-on-test-set)
9. [Final Report](#final-report)

## Technologies Used

- Python - version 3.12.3
- Pandas - version 2.2.2
- Numpy - version 1.26.4
- Matplotlib - version 3.7.1
- Seaborn - version 0.13.2
- Sklearn - version 1.5.1
- Statsmodels - version 0.14.2

## Acknowledgements

- This project was inspired by IIITB and Upgrad's Lecture on EDA
- References:
  - [Seaborn Documentation](https://seaborn.pydata.org/)

## Contact

Created by [Raja](https://github.com/RajaKalavala)
