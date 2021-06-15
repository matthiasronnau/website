---
title: Social Network Analysis
summary: Performing a network analysis for a large online store.
tags:
- Irvine
- R
date: "2021-03-18T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by Alinea Grubnyak on Unsplash
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  name: GitHub Repository
  url: https://github.com/matthiasronnau/BANA-277-Final-Project
- icon: kaggle
  icon_pack: fab
  name: Dataset
  url: https://www.kaggle.com/mkechinov/ecommerce-behavior-data-from-multi-category-store
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

For the final project in BANA-277, Customer and Social Analytics, our team performed a network analysis for data from a multi-category online store. We utilized the [igraph package](https://igraph.org/r/) in R to build our network, visualize the connections between items in the store, and generate network statistics such as hub and authority scores.

The [original data](https://www.kaggle.com/mkechinov/ecommerce-behavior-data-from-multi-category-store) contained event level customer data, and many hours were dedicated to transforming the data so that we could get it to work with igraph. Along the way, I developed a [small R package](https://github.com/matthiasronnau/graphdata) that will take in data of this form and return an igraph object. Building this R package was a fun, challenging, and rewarding side project that allowed me to explore the developer side of R, something that I have not had much experience with before.

Our analysis of the data showed the effects that coronavirus has had on consumer's spending habits: the most frequently purchased items were electronic devices, appliances, and construction equipment. We concluded that this was likely driven by people spending more time at home working remotely, cooking, and working on home-improvement projects. In addition to our network analysis, we constructed a logistic regression to determine what factors influence a user's propensity to make a purchase of a product. Overall, we had a fun time implementing the skills and techniques that we learned in the class to analyze the data.
