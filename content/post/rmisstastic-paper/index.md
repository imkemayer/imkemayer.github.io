+++
title = "New paper: R-miss-tastic: a unified platform for missing values methods and workflows"
#subtitle = "Consistency results for treatment effect estimation with missing values."

date = 2019-08-15T00:00:00
lastmod = 2019-08-15T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Imke Mayer", "Julie Josse", "Nicholas Tierney", "Nathalie Vialaneix"]

tags = ["R", "missing-values", "missing-data"]
summary = "Our new paper presents 'R-miss-tastic', a platform that aims to provide an overview of standard missing values problems, methods, how to handle them in analyses, and relevant implementations of methodologies. The objective is not only to collect, but also comprehensively organize materials, to create standard analysis workflows, and to unify the community."

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["r-miss-tastic"]

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
[image]
  # Caption (optional)
   caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""

  # Show image only in page previews?
  preview_only = false

+++

Missing values are unavoidable when working with data. Their occurrence is exacerbated as more data from different sources become available. However, most statistical models and visualization methods require complete data, and improper handling of missing data results in information loss, or biased analyses. Since the seminal work of Rubin (1976), there has been a burgeoning literature on missing values with heterogeneous aims and motivations. This has resulted in the development of various methods, formalizations, and tools (including a large number of R packages). However, for practitioners, it is challenging to decide which method is most suited for their problem, partially because handling missing data is still not a topic systematically covered in statistics or data science curricula. 

To help address this challenge, we - that is [Julie Josse](http://juliejosse.com/), [Nathalie Vialaneix](http://www.nathalievialaneix.eu/), [Nick Tierney](https://www.njtierney.com/) and myself - have launched a unified platform: ["R-miss-tastic"](https://rmisstastic.netlify.com/), which aims to provide an overview of standard missing values problems, methods, how to handle them in analyses, and relevant implementations of methodologies. The objective is not only to collect, but also comprehensively organize materials, to create standard analysis workflows, and to unify the community. These overviews are suited for beginners, students, more advanced analysts and researchers.

In our new [paper](https://arxiv.org/abs/1908.04822), we present in detail the different sections of the platform, the choices that have been made, and the targeted audience. We also give an overview of the planed future development for the platform. 

If you are interested in contributing to the platform, for instance with materials or active help in the future development of R-miss-tastic, feel free to contact us by e-mail at r-miss-tastic@clementine.fr!

For a first version of our paper [click here](https://arxiv.org/abs/1908.04822).
