---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: portfolio

# Activate this widget? true/false
active: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 65

title: Projects
subtitle: "These are some of the interesting projects that I have worked on while a student at the University of California, Berkeley and the University of California, Irvine. They encompass some of the various statistical and machine learning techniques that I have learned.

The GitHub Repository for each project is linked on the project page, as well as links to the data that I used (if applicable). If you have any questions, don't hesitate to [reach out to me](mailto:matthias.ronnau@uci.edu)!""

content:
  # Page type to display. E.g. project.
  page_type: project

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
  - name: All
    tag: '*'
  - name: Berkeley
    tag: Berkeley
  - name: Irvine
    tag: Irvine
  - name: R
    tag: R
  - name: Python
    tag: Python
  - name: Sampling
    tag: Sampling
  - name: Regression
    tag: Regression
  - name: Machine Learning
    tag: Machine Learning
  - name: Package
    tag: Package

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '2'

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view: 3

  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
---
