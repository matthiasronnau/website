---
title: National Drug Use Survey Analysis
summary: Analyzing drug use among different segments of the population.
featured: true
tags:
- Berkeley
- Sampling
- R
date: "2020-05-15T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by Online Marketing on Unsplash
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  name: GitHub Repository
  url: https://github.com/matthiasronnau/Stat-152-Survey-Project
- icon: database
  icon_pack: fas
  name: Dataset
  url: https://www.icpsr.umich.edu/web/ICPSR/studies/9833/summary?fbclid=IwAR30t8KImNd5QorUaLWMCtsQydUTweSdFoIJPyNR92hXwBHy9XKtiCnSg1Y
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

The motivation behind this project was to take data from a complex national survey, pose questions about the data, and use the data to answer our questions. The data for this project was acquired from the [ICSPR website](https://www.icpsr.umich.edu/web/ICPSR/studies/9833/summary?fbclid=IwAR30t8KImNd5QorUaLWMCtsQydUTweSdFoIJPyNR92hXwBHy9XKtiCnSg1Y), and is part of the National Survey on Drug Use and Heath (NSDUH), specifically focusing on drug abuse, from 1990. The packages readr, survey, and VIM were all used for our analysis. The package readr was used for loading the data, the survey package was used for constructing our estimates and making our visualizations, and VIM was used for hot deck imputation of missing values.
