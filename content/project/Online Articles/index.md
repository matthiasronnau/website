---
title: Online News Popularity Analysis
summary: Analyzing features from Mashable articles to determine what characteristics make online news articles popular.
featured: true
tags:
- Irvine
- Python
- Machine Learning
date: "2020-12-09T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by Glenn Carstens-Peters on Unsplash
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  name: GitHub Repository
  url: https://github.com/matthiasronnau/BANA-273-Term-Project
- icon: database
  icon_pack: fas
  name: Dataset
  url: https://archive.ics.uci.edu/ml/datasets/online+news+popularity
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

The growth of the internet and technology has contributed to the popularity of online news articles and blogs. While print news is not completely dead yet, a growing number of people prefer to search the web for the day’s happenings, as online news is free, immediate, and convenient. In fact, in 2018 Pew Research noted that just over 50% of Americans get their news from some online format.  According to Forbes, the number had increased to 55% in 2019.  

For our BANA-273, Machine Learning for Analytics, Term Project, our team used data on Mashable articles from a two-year period to build a few machine learning models that predict the popularity of an article given a set of features about that article, such as the number of words in the article, the day of the week the article was published on, and the average sentiment polarity of the article content. In order to run these models, we discretized the continuous prediction variable “shares” into two categories: “High” popularity for those articles with a number of shares greater than or equal to the median number of shares for all articles, and “Low” popularity for those articles with a number of shares less than the median number of shares for all articles.

In order to predict the popularity of a given article, we built three machine learning models using Naïve Bayes, Random Forest, and K-Nearest Neighbors (KNN) algorithms. Overall, the accuracies we received from all three models were low and were unable to be improved much with the various data processing methods that we utilized. In fact, different method of data processing actually reduced the accuracies for various models. However, we found that implementing a Random Forest model while using supervised discretization (while not “looking” at the test set) gave us the best results at 64.91% overall.

Our team used Python for the majority of the models we built, and we used WEKA to run the models with supervised discretization. For more information on our techniques as well as our code, please check out the GitHub link above.
