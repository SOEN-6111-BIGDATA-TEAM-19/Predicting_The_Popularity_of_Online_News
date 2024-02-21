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

The foundation of our analysis is a Dataset comprising of **39,797** online news articles, each characterized by **61 attributes** detailing content structure, style, and context. 
Attributes include following types of metrics:
- Textual metrics like word count and uniqueness, Multimedia element count (images and videos), publication timing, content category (e.g., lifestyle, entertainment, business), and sentiment analysis. 
- SEO-related keywords performance and article linkage (internal and external) are tracked. 
- Latent Dirichlet Allocation (LDA) topics to gauge content themes. 
- The target variable, "shares," represents article popularity, offering a quantitative measure of social interactions. 

All the attirbutes with their description are listed here: https://github.com/SOEN-6111-BIGDATA-TEAM-19/Predicting_The_Popularity_of_Online_News/wiki/Dataset-Features 

This rich dataset enables a comprehensive analysis of factors influencing news article engagement.

## Research Questions

Our investigation revolves around two core research questions:

* Impact of Article Features: Which factors significantly influence the popularity of online news? What is the relationship between specific article attributes (e.g., title length, multimedia usage) and the number of social interactions(popularity)?
* Influence of Content Type and Distribution Channels: How do different content types (technology, entertainment, business) and distribution channels affect article popularity?

## Model Design and Algorithms

To tackle these questions, the **class of models** that we will employ are a suite of **regression models** since they are best suited for predicting continuous variables such as article shares. 

_Algorithms that we would use for comparison are:_

- **Linear Regression** for establishing a baseline understanding of linear feature relationships. This algorithm will help us in getting clear insights into which features have a linear relationship with article popularity, helping to identify straightforward strategies for content optimization.

- **Random Forest Regression** to capture complex, non-linear feature interactions. This will help us to understand the combined effect of multiple features on shares/popularity, including interaction effects, and identify the most influential predictors through its feature importance scores.

- **Gradient Boosting Regression** for iterative error correction and performance optimization. With this algorithm we are hoping to that it would be particularly beneficial for addressing the dataset's varied and nuanced features, leading to potentially higher accuracy in forecasting article shares.

## Evaluation Metrics

Model performance will be assessed using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and Mean Squared Error (MSE), ensuring a comprehensive evaluation of accuracy and predictive quality.
