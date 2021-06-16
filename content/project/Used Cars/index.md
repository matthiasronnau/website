---
title: Used Car Listings Analysis
summary: Analyzing used car listings from Craigslist to predict the price of a used car.
featured: true
tags:
- Irvine
- Python
- Regression
- Machine Learning
date: "2020-12-15T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by Karen Vardazaryan on Unsplash
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  name: GitHub Repository
  url: https://github.com/matthiasronnau/BANA-212-Final-Project
- icon: kaggle
  icon_pack: fab
  name: Dataset
  url: https://www.kaggle.com/austinreese/craigslist-carstrucks-data
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

For our final project for BANA-212, Data and Programming for Analytics, our team sought to analyze used car listings from Craigslist in order to understand the important factors that go into a used car's listing price. We used Python and built in libraries for our analysis; more information on the packages used as well as our code can be found at the GitHub link above.

Buying a used car online is easier than it has ever been. In 2019, there were almost 41 million used cars sold in the United States, compared to only 17 million new car sales. Additionally, the coronavirus pandemic has made the used car market surge to levels it hasn’t seen in over 50 years. Used cars are often more affordable of an investment than purchasing a brand-new vehicle from the dealership, which partially explains why there is consistently a larger volume of used cars purchased per year than new cars; other reasons include purchasing “project” cars, purchasing rare cars that are hard to find, and purchasing older vehicles that are not made anymore. With such a large and growing demand for used cars, our team sought to analyze what features of a used car tend to increase its resale price.

Overall, two of our models performed quite well, with the linear regression showing a strong correlation with the predictors and the random forest giving a decent overall accuracy; unfortunately, Naïve Bayes did not perform as well. We attempted using just the most important variables to build our machine learning models (by using the variables that shared the most mutual information with the price category), but this ended up reducing the overall accuracies.

Our team found that the model year and the odometer had the most important impact on the price of a used car, and intuitively, this makes sense; older cars with more miles on them are likely to have more issues and thus be worth less.
