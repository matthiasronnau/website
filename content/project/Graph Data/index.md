---
title: Social Network R Package
summary: Custom R package for transforming customer level data into an iGraph object.
featured: true
tags:
- Irvine
- R
- Package
date: "2021-03-18T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by JJ Ying on Unsplash
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  name: GitHub Repository
  url: https://github.com/matthiasronnau/graphdata
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

This R Package was developed in conjunction with the [final project for BANA-277, Customer and Social Analytics](https://www.matthiasronnau.com/project/social-network/). The data that we used in this project was event level customer data and was not suitable to use with iGraph, as this package requires data to be in two columns, a "Source" and a "Target" node ("Source" products point to "Target" products). This package transforms a given dataframe of this type and returns an iGraph object; it takes as parameters a user ID and a product ID.
