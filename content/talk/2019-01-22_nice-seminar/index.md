+++
title = "Causal Inference with Missing Values: Treatment Effect Estimation of Tranexamic Acid on Mortality for Traumatic Brain Injury Patients (Talk given by Julie Josse)"
date = 2019-01-08T00:00:00  # Schedule page publish date.
draft = false

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
time_start = 2019-01-22T16:00:00
startDate = 2019-01-22T16:00:00
#time_end = 2030-06-01T15:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Imke Mayer", "Julie Josse", "Jean-Pierre Nadal", "Tobias Gauss", "Jean-Denis Moyer"]

# Abstract and optional shortened version.
abstract = "In healthcare or social sciences research, prospective observational studies are frequent, relatively easily put in place (compared to experimental randomized trial studies for instance) and can allow for different kinds of posterior analyses such as causal inferences. Average treatment effect (ATE) estimation for instance is possible through the use of propensity scores which allow to correct for treatment assignment biases in the non-randomized study design. However, a major caveat of large observational studies is their complexity and incompleteness: the covariates are often taken at different levels and stages, they can be heterogeneous – categorical, discrete, continuous – and almost inevitably contain missing values. The problem of missing values in causal inference has long been ignored and only recently gained some attention due to the non-negligible impacts in terms of power and bias induced by complete case analyses. We compare several IPW and doubly robust average treatment effect estimators which either directly account for missing values or are complete case ATE estimators applied on imputed data, i.e. on complete data obtained by replacing every missing value by at least one plausible one, and to the recently proposed method of Kallus et al. [2018]. We assess the performance of our estimators on a large prognostic database containing detailed information about over 15,000 severely traumatized patients in France. Using the proposed ATE estimators and this database we study the effect on mortality of tranexamic acid administration to patients with traumatic brain injury in the context of critical care management."
abstract_short = "We compare several IPW and doubly robust average treatment effect estimators which either directly account for missing values or are complete case ATE estimators applied on imputed data, i.e. on complete data obtained by replacing every missing value by at least one plausible one, and to the recently proposed method of Kallus et al. [2018]. We assess the performance of our estimators on a large prognostic database containing detailed information about over 15,000 severely traumatized patients in France."

# Name of event and optional event URL.
event = "Séminaire de Probabilités et Statistique"
event_url = "https://math.unice.fr/seminairesequipeps/séminaire-de-léquipe-de-probabilités-et-statistique.html"

# Location of event.
location = "Université de Nice Sophia-Antipolis, Nice, France"

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
url_slides = "slides/2019-01-22_NiceStatSeminar_Slides.pdf"
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
