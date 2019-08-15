+++
title = "Doubly robust treatment effect estimation with incomplete confounders"
date = 2019-06-28T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Imke Mayer", "Julie Josse", "Stefan Wager"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["0"]

# Publication name and optional abbreviated version.
#publication = "In *Signal Image Technology & Internet Systems (SITIS)*, IEEE."
#publication_short = "In *SITIS*"

# Abstract and optional shortened version.
abstract = "In healthcare and social sciences research, prospective observational studies are frequent, relatively easily put in place (compared to experimental randomized trial studies for instance) and can allow for different kinds of posterior analyses such as causal inferences. Average treatment effect (ATE) estimation for instance is possible through the use of propensity scores which allow to correct for treatment assignment biases in the non-randomized study design. However, a major caveat of large observational studies is their complexity and incompleteness: the covariates are often taken at different levels and stages, they can be heterogeneous – categorical, discrete, continuous – and almost inevitably contain missing values. The problem of missing values in causal inference has long been ignored and only recently gained some attention due to the non-negligible impacts in terms of bias induced by complete case analyses and misspecified imputation models. We discuss conditions under which causal inference can be possible despite missing confounder values, namely unconfoundedness on the observed values; we propose two alternative ATE estimators which directly account for the missing values, the first is built on logistic-linear specification and observed likelihood, appropriate for data missing at random, while the second uses semi-parametric estimation based on random forests with the great advantage of handling data missing not at random. We compare these two estimators to different methods proposed in the past to deal with missing confounder values. We assess the performance of our estimators on a large prospective database containing detailed information about over 20,000 severely traumatized patients in France. Using the proposed ATE estimators and this database we study the effect on mortality of tranexamic acid administration to patients with traumatic brain injury in the context of critical care management."
abstract_short = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "papers/2019-06-25_DR-TreatmentEffect-WithMissingValues.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = "posters/2019-06-25_DS3_poster.pdf"
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = ""

# Does this page contain LaTeX math? (true/false)
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "" #"Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++

<!-- More detail can easily be written here using *Markdown* and $\rm \LaTeX$ math code. -->
