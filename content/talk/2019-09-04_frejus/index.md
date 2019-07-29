+++
title = "Doubly-robust treatment effect estimation with incomplete confounders"
date = 2019-08-01T00:00:00  # Schedule page publish date.
draft = false

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
time_start = 2019-09-03T17:00:00
startDate = 2019-09-03T17:00:00
#time_end = 2030-09-03T15:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Imke Mayer", "Julie Josse", "Stefan Wager"]

# Abstract and optional shortened version.
abstract = "The problem of missing values in causal inference has long been ignored and only recently gained some attention due to the non-negligible impacts in terms of bias induced by complete case analyses and misspecified imputation models. We discuss conditions under which causal inference can be possible despite missing confounder values, namely unconfoundedness on the observed values. We propose two average treatment effect (ATE) estimators, each in an inverse propensity weighting and a double-robust form, which directly account for the missing values and show their consistency. The first is built on logistic-linear specification and observed likelihood, appropriate for data missing at random, while the second uses semi-parametric estimation based on random forests with the great advantage of handling data missing not at random. We compare these two estimators to different methods available in an extensive simulation study.
We apply the estimators on a large prospective database about over 20,000 severely traumatized patients in France to study the effect on mortality of tranexamic acid administration to patients with traumatic brain injury in the context of critical care management."
abstract_short = "We propose two average treatment effect (ATE) estimators, each in an inverse propensity weighting and a double-robust form, which directly account for the missing values and show their consistency."

# Name of event and optional event URL.
event = "Statistique Mathématique et Applications"
event_url = "https://statmathappli.mia.inra.fr/fr"

# Location of event.
location = "Villa Clythia, Fréjus, France"

# Is this a selected talk? (true/false)
selected = false

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
tags = ["causal-inference", "missing-values"]

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
