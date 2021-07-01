+++
title = "Transporting treatment effects with incomplete attributes"
date = 2021-05-01T00:00:00  # Schedule page publish date.
draft = false

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
time_start = 2021-07-02T14:40:00
startDate = 2021-07-02T14:40:00
#time_end = 2030-12-03T16:00:00

#eventStatus = "https://schema.org/EventRescheduled"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Imke Mayer"]

# Abstract and optional shortened version.
abstract = "The simultaneous availability of experimental and observational data to estimate a treatment effect is both an
opportunity and a statistical challenge: Combining the information gathered from both data is a promising
avenue to build upon the internal validity of randomized controlled trials (RCTs) and a greater external validity
of observational data, but it raises methodological issues, especially due to different sampling designs inducing
distributional shifts. We focus on the aim of transporting a causal effect estimated on an RCT onto a target
population described by a set of covariates. Available methods such as inverse propensity weighting are not
designed to handle missing values, which are however common in both data. In addition to coupling the
assumptions for causal identifiability and for the missing values mechanism and to defining appropriate
strategies, one has to consider the specific structure of the data with two sources and treatment and outcome
only available in the RCT. We study different approaches and their underlying assumptions on the data generating processes and
distribution of missing values and suggest several adapted methods, in particular multiple imputation
strategies. These methods are assessed in an extensive simulation study and practical guidelines are provided for
different scenarios. This work is motivated by the analysis of a large registry of over 20,000 major trauma patients and a multicentered RCT studying the effect of tranexamic acid administration on mortality."
abstract_short = "The simultaneous availability of experimental and observational data to estimate a treatment effect is both an
opportunity and a statistical challenge: Combining the information gathered from both data is a promising
avenue to build upon the internal validity of randomized controlled trials (RCTs) and a greater external validity
of observational data, but it raises methodological issues, especially due to different sampling designs inducing
distributional shifts."

# Name of event and optional event URL.
event = "European Causal Inference Meeting (EuroCIM)"
event_url = "https://www.eurocim.org/"

# Location of event.
location = "Virtual (hosted by the Department of Statistics of the London School of Economics)"

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
