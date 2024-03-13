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

The primary goal of this project is to accurately predict the popularity of online news articles, with popularity specifically defined by the level of social interactions, such as the number of shares an article receives. To achieve this, we will employ advanced machine learning techniques to analyze and model how various attributes of news articles contribute to their likelihood of being shared widely across social networks.

## Dataset Overview

The foundation of our analysis is a Dataset comprising of **39,797** online news articles, each characterized by **61 attributes** detailing content structure, style, and context. 
Attributes include following types of metrics:
- Textual metrics like word count and uniqueness, Multimedia element count (images and videos), publication timing, content category (e.g., lifestyle, entertainment, business), and sentiment analysis. 
- SEO-related keywords performance and article linkage (internal and external) are tracked. 
- Latent Dirichlet Allocation (LDA) topics to gauge content themes. 
- The target variable, "shares," represents article popularity, offering a quantitative measure of social interactions. 

All the attributes with their description are listed here: [Attribute List](https://github.com/SOEN-6111-BIGDATA-TEAM-19/Predicting_The_Popularity_of_Online_News/blob/main/resources/AttributeDescription.md)

This rich dataset enables a comprehensive analysis of factors influencing news article engagement.

## Research Questions

Our investigation revolves around two core research questions:

* Popularity of Online News: How do article features (e.g., title length, multimedia usage), content types (technology, entertainment, business), and distribution channels influence the share and popularity of online news, and is it possible to accurately forecast reader engagement and social interactions?

## Model Design and Algorithms

To tackle these questions, the **class of models** that we will employ are a suite of **regression models** since they are best suited for predicting continuous variables such as article shares. 

_Algorithms that we would use for comparison are:_

- **Linear Regression** for establishing a baseline understanding of linear feature relationships. This algorithm will help us in getting clear insights into which features have a linear relationship with article popularity, helping to identify straightforward strategies for content optimization.

- **Random Forest Regression** to capture complex, non-linear feature interactions. This will help us to understand the combined effect of multiple features on shares/popularity, including interaction effects, and identify the most influential predictors through its feature importance scores.

- **Gradient Boosting Regression** for iterative error correction and performance optimization. With this algorithm we are hoping to that it would be particularly beneficial for addressing the dataset's varied and nuanced features, leading to potentially higher accuracy in forecasting article shares.

## Evaluation Metrics

Model performance will be assessed using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and Mean Squared Error (MSE), ensuring a comprehensive evaluation of accuracy and predictive quality.
