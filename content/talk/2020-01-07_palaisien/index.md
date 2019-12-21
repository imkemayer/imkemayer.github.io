+++
title = "Treatment effect estimation with missing attributes"
date = 2019-12-20T00:00:00  # Schedule page publish date.
draft = false

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
time_start = 2020-01-07T16:00:00
startDate = 2020-01-07T17:00:00
#time_end = 2030-12-03T16:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Imke Mayer"]

# Abstract and optional shortened version.
abstract = "Inferring causal effects of a treatment or policy from observational data is central to many applications. However, state-of-the-art methods for causal inference seldom consider the possibility that covariates have missing values, which is ubiquitous in many real-world cases.

This work is motivated by assessing several medical questions about different treatments based on a large prospective database counting over 20,000 major trauma patients. This database is complex in the sense that it presents a multi-level and heterogeneous structure and precisely contains large fractions of missing values.

Missing data greatly complicate causal analyses as they either require strong assumptions about the missing data generating mechanism or an adapted unconfoundedness hypothesis. In this talk, I will first provide a classification of existing methods according to the main underlying assumptions, which are based either on variants of the classical unconfoundedness assumption or relying on assumptions about the mechanism that generates the missing values. Then, I will present two recent contributions on this topic: (1) an extension of doubly robust estimators that allows handling of missing attributes, and (2) an approach to causal inference based on variational autoencoders adapted to incomplete data."
abstract_short = "TBA."

# Name of event and optional event URL.
event = "Séminaire palaisien"
event_url = "https://palaisien.herokuapp.com/about/"

# Location of event.
location = "CentraleSupélec, Gif-sur-Yvette, France"

# Is this a selected talk? (true/false)
selected = true

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects = ["internal-project"]
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["causal-inference", "missing-values", "machine-learning"]

# Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Does the content use math formatting?
math = false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  #caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++
