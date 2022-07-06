---
layout: splash
title: " " 
permalink: /skincareaddiction/
date: 2021-01-12
tags: [Data Mining and Wrangling]
header:
  image: /assets/images/skincare_poster.jpg
---

## Beauty in Big Data: r/SkincareAddiction Topic Modelling
*Edeza, Obrero, Pagobayan, Tabong (Asian Institute of Management)*

### Executive Summary

We set out to text mine the r/SkincareAddiction subreddit for actionable clusters via LDA Topic Modelling. To do this we extract comments from February to April 2020, and then wrangle the data via tokenization, removal of stopwords, lemmatization, and building bi-gram and tri-gram models. Such quantities of data were vast and required the use of a Dask cluster to properly processes. We were able to generate 15 distinct and actionable topics from the data and displayed them via wordclouds. Such topics will be able to help businesses and consumers alike in understanding products and the nature of the skin care industry. Going forward we believe that incorporation of ingredient and usage quantity will be beneficial for further research. This will help businesses understand how much the of their product the general audience actually uses. The knowledge may have implications for a firm’s manufacturing and marketing decisions. Moreover, understanding how time plays a role in the data will help enrich the analysis even further.

### Business Value

The skin care industry has experienced significant growth from the past years. In fact, Euromonitor forecasts an annual market growth of 8% from 2020 to 2025 [1]. The market remains strong as consumers look for higher-value products that caters to their specific skin characteristics [1].The subreddit r/SkincareAddiction provides consumers additional information through interactions from reddit users. In this platform, they share skin care routine tips, product reviews, and other recommendations that covers a multitude of topics related to the skin care industry. Uncovering key topics from the r/SkincareAddiction subreddit would provide value to the following stakeholders.
Skin care consumers would gain more knowledge on what types of products to buy. The topics formed could serve as their initial list of product ingredients or brands to look at as they search for the right product. This would enable them to make more informed decisions in selecting the right products that fit the needs of their skin.
The themes would also provide value to skin care manufacturers since they would be able to identify niche markets from unique topics. Moreover, their research and development would have valuable insights based on the popular product ingredients shown in the topics. Lastly, the insights would allow them to pivot their strategy or further improve their value proposition by offering something unique from the market.
Online resellers of skin care products would also benefit from this study. This would enable online resellers to expand their product offerings based on what is popular in the subreddit.

[1] Anuwong, W. (2020). Skin Care in the Philippines Analysis. Country Report. Euromonitor International.

*Full text article and source codes can be provided upon request.*