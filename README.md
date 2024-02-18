# SOEN 6111 BigData Project - Team 19
## Project Title: Predicting the Popularity of Online News

**_Project Members:_**
- Rancy Chadha ()
- Sarabpreet Singh Rekhi ()
- Wei Qi (40198872)
- Wenxue Zhao	 ()

## Project Description
This project aims to predict which online news articles will become popular (based on the number of social interactions) by analyzing various statistical data related to news articles. <br><br>
The dataset involved in the study contains 61 attributes of 39,797 news articles, "shares" is the target field.

|Attribute|Description|
| :---: | :--- |
|url|URL of the article|
|timedelta|Days between the article publication and the dataset acquisition|
|n_tokens_title|Number of words in the title|
|n_tokens_content|Number of words in the content|
|n_unique_tokens|Rate of unique words in the content|
|n_non_stop_words|Rate of non-stop words in the content|
|n_non_stop_unique_tokens|Rate of unique non-stop words in the content|
|num_hrefs|Number of links|
|num_self_hrefs|Number of links to other articles published by Mashable|
|num_imgs|Number of images|
|num_videos|Number of videos|
|average_token_length|Average length of the words in the content|
|num_keywords|Number of keywords in the metadata|
|data_channel_is_lifestyle|Is data channel 'Lifestyle'?|
|data_channel_is_entertainment|Is data channel 'Entertainment'?|
|data_channel_is_bus|Is data channel 'Business'?|
|data_channel_is_socmed|Is data channel 'Social Media'?|
|data_channel_is_tech|Is data channel 'Tech'?|
|data_channel_is_world|Is data channel 'World'?|
|kw_min_min|Worst keyword (min. shares)|
|kw_max_min|Worst keyword (max. shares)|
|kw_avg_min|Worst keyword (avg. shares)|
|kw_min_max|Best keyword (min. shares)|
|kw_max_max|Best keyword (max. shares)|
|kw_avg_max|Best keyword (avg. shares)|
|kw_min_avg|Avg. keyword (min. shares)|
|kw_max_avg|Avg. keyword (max. shares)|
|kw_avg_avg|Avg. keyword (avg. shares)|
|self_reference_min_shares|Min. shares of referenced articles in Mashable|
|self_reference_max_shares|Max. shares of referenced articles in Mashable|
|self_reference_avg_sharess|Avg. shares of referenced articles in Mashable|
|weekday_is_monday|Was the article published on a Monday?|
|weekday_is_tuesday|Was the article published on a Tuesday?|
|weekday_is_wednesday|Was the article published on a Wednesday?|
|weekday_is_thursday|Was the article published on a Thursday?|
|weekday_is_friday|Was the article published on a Friday?|
|weekday_is_saturday|Was the article published on a Saturday?|
|weekday_is_sunday|Was the article published on a Sunday?|
|is_weekend|Was the article published on the weekend?|
|LDA_00|Closeness to LDA topic 0|
|LDA_01|Closeness to LDA topic 1|
|LDA_02|Closeness to LDA topic 2|
|LDA_03|Closeness to LDA topic 3|
|LDA_04|Closeness to LDA topic 4|
|global_subjectivity|Text subjectivity|
|global_sentiment_polarity|Text sentiment polarity|
|global_rate_positive_words|Rate of positive words in the content|
|global_rate_negative_words|Rate of negative words in the content|
|rate_positive_words|Rate of positive words among non-neutral tokens|
|rate_negative_words|Rate of negative words among non-neutral tokens|
|avg_positive_polarity|Avg. polarity of positive words|
|min_positive_polarity|Min. polarity of positive words|
|max_positive_polarity|Max. polarity of positive words|
|avg_negative_polarity|Avg. polarity of negative  words|
|min_negative_polarity|Min. polarity of negative  words|
|max_negative_polarity|Max. polarity of negative  words|
|title_subjectivity|Title subjectivity|
|title_sentiment_polarity|Title polarity|
|abs_title_subjectivity|Absolute subjectivity level|
|abs_title_sentiment_polarity|Absolute polarity level|
|shares|Number of shares (target)|

## Research Questions
1. Which factors significantly influence the popularity of online news? 
> This question explores how different features (such as title length, content length, number of images, number of videos, time of publication, etc.) affect the number of social interactions with news articles.

2. What are the differences in popularity among different types of content (such as technology, entertainment, business, etc.)? 
> Analyze the impact of data channels on the popularity of news, understanding which themes or domains are more likely to receive high levels of social interaction.

## Evaluation Metrics
