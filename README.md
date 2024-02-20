# $${\color{#088da5}Project \space Title: \space Predict \space Popularity \space Of \space Online \space News}$$

## SOEN 6111 BigData Project
_Team Name:_ **TEAM 19**

**_Project Members:_**
| Name                    | ID       |
|-------------------------|----------|
| Rancy Chadha            | 40221591 |
| Sarabpreet Singh Rekhi  | 40154067 |
| Wei Qi                  | 40198872 |
| Wenxue Zhao             | 40187305 |

## Project Definition and Objectives

In this project we intend to leverage machine learning techniques to predict the popularity of online news articles, as measured by social interactions such as shares. Our objective is to dissect a wide array of article attributes to find the determinants of reader engagement and article virality. In doing so, we aim not only to forecast article popularity but also to offer actionable insights into how different content characteristics affect public interest and engagement.

By examining the influence of article features and the role of content type and distribution channels, this project seeks to provide a nuanced understanding of digital content dynamics.

## Dataset Overview

The foundation of our analysis is a Dataset encompassing **61 attributes** across **39,797 news articles**. These attributes cover a broad spectrum, including basic metrics like_ word counts, multimedia elements_, and advanced indicators such as _keyword performance and sentiment analysis_. The "shares" attribute, indicating the article's popularity, serves as our target variable. This extensive Dataset offers a fertile ground for exploring the multifaceted nature of content engagement.

## Research Questions

Our investigation revolves around two core research questions:

* Impact of Article Features: What is the relationship between specific article attributes (e.g., title length, multimedia usage) and the level of social interaction?
* Influence of Content Type and Distribution Channels: How do different content types (technology, entertainment, business) and distribution channels affect article popularity?

## Model Design and Algorithms

To tackle these questions, the **class of models** that we will employ are a suite of **regression models** since they are best suited for predicting continuous variables such as article shares. 

_Algorithms that we would use for comparison are:_

* Linear Regression for establishing a baseline understanding of linear feature relationships.
* Random Forest Regression to capture complex, non-linear feature interactions.
* Gradient Boosting Regression for iterative error correction and performance optimization.

## Evaluation Metrics

Model performance will be assessed using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and Mean Squared Error (MSE), ensuring a comprehensive evaluation of accuracy and predictive quality.
