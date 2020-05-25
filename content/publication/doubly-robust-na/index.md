+++
title = "Doubly robust treatment effect estimation with missing attributes"
date = 2019-06-28T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Imke Mayer", "Erik Sverdrup", "Tobias Gauss", "Jean-Denis Moyer", "Stefan Wager", "Julie Josse"]

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
publication = "In *Annals of Applied Statistics*, AOAS."
publication_short = "In *AOAS*"

# Abstract and optional shortened version.
abstract = "The problem of missing values in causal inference has long been ignored and only recently gained some attention due to the non-negligible impacts in terms of bias induced by complete case analyses and misspecified imputation models. We discuss different conditions under which causal inference can be possible despite missing attributes, we review existing solutions and propose a new approach to handle missing attributes in treatment effect estimation. We propose two average treatment effect (ATE) estimators, each in an inverse propensity weighting and a doubly robust form, which directly account for the missing values and show their consistency. The first is built on logistic-linear specification and observed likelihood, appropriate for data missing at random, while the second uses semi-parametric estimation based on random forests with the great advantage of handling data missing not at random. We compare these two estimators to different methods available in an extensive simulation study. We apply the estimators on a large prospective database counting about over 20,000 severely traumatized patients in France to study the effect on mortality of tranexamic acid administration among patients with traumatic brain injury in the context of critical care management."
abstract_short = "*To appear in Annals of Applied Statistics*"

# Is this a selected publication? (true/false)
selected = true

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
url_pdf = "papers/2019-10-23_DR-TreatmentEffect-WithMissingAttributes.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = "slides/2019-09-03_Frejus_Slides.pdf"
url_video = ""
url_poster = "posters/2019-06-25_DS3_poster.pdf"
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [{name = "Supplementary material", url = "papers/2020-05-17_DR-TreatmentEffect-WithMissingAttributes_supp.pdf"}]

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
