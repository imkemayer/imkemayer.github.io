+++
title = "Causal inference methods for combining randomized trials and observational studies"
date = 2021-05-01T00:00:00  # Schedule page publish date.
draft = false

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
time_start = 2021-06-25T12:30:00
startDate = 2021-06-25T12:30:00
#time_end = 2030-12-03T16:00:00

#eventStatus = "https://schema.org/EventRescheduled"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Imke Mayer", "Bénédicte Colnet"]

# Abstract and optional shortened version.
abstract = "With increasing data availability, treatment causal effects can be evaluated across different datasets, both randomized trials and observational studies. Randomized trials isolate the effect of the treatment from that of unwanted (confounding) co-occurring effects. But they may be applied to limited populations, and thus lack external validity. On the other hand, large observational samples are often more representative of the target population but can conflate confounding effects with the treatment of interest. In this work, we review the growing literature on methods for causal inference on combined randomized trial and observational studies, striving for the best of both worlds. We first discuss identification and estimation methods that improve generalizability of randomized controlled trials (RCTs) using the representativeness of observational data. Classical estimators include weighting, difference between conditional outcome models, and double robust estimators. We then discuss methods that combine RCTs and observational data to improve the (conditional) average treatment effect estimation, handling possible unmeasured confounding in the observational data. We also connect and contrast works developed in both the potential outcomes framework and the structural causal models framework. This work is motivated by a large prospective database counting about over 20,000 severely traumatized patients in France and a multi-centered international randomized clinical trial studying the effect of tranexamic acid administration on mortality among patients with traumatic brain injury. The former is complex in the sense that it presents a multi-level and heterogeneous structure and contains large fractions of missing values, the latter contains a more homogeneous and restrictive patient population. Based on these two databases we are interested in assessing the external and internal validity of both studies. This is a joint work with Bénédicte Colnet, Gaël Varoquaux, Jean-Philippe Vert, Julie Josse, Shu Yang and others."
abstract_short = "With increasing data availability, treatment causal effects can be evaluated across different datasets, both randomized trials and observational studies. Randomized trials isolate the effect of the treatment from that of unwanted (confounding) co-occurring effects. But they may be applied to limited populations, and thus lack external validity. On the other hand, large observational samples are often more representative of the target population but can conflate confounding effects with the treatment of interest. In this work, we review the growing literature on methods for causal inference on combined randomized trial and observational studies, striving for the best of both worlds."

# Name of event and optional event URL.
event = "Working Group on Risk"
event_url = "http://crear.essec.edu/working-group-on-risk"

# Location of event.
location = "Virtual (hosted by ESSEC Business School and CREAR, France)"

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
