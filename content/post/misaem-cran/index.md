+++
title = "R package: misaem is back on CRAN"
subtitle = "After a short period of absence, misaem is again available on CRAN."

date = 2021-04-12T00:00:00
lastmod = 2021-04-12T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Julie Josse", "Wei Jiang", "Pavlo Mozharovskyi", "Imke Mayer"]

tags = ["R-package","missing-values"]
summary = "Estimate parameters of linear regression and logistic regression with missing covariates with missing data, perform model selection and prediction, using EM-type algorithms. Jiang W., Josse J., Lavielle M., TraumaBase Group (2020)."

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects = ["internal-project"]

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder.
[image]
  # Caption (optional)
  # caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  #focal_point = ""

  # Show image only in page previews?
  #preview_only = false

+++

misaem is a package to perform linear regression and logistic regression with missing data, under MCAR (Missing completely at random) and MAR (Missing at random) mechanisms. The covariates are assumed to be continuous variables. The methodology implemented is based on maximization of the observed likelihood using EM-types of algorithms. It has been written by Wei Jiang (former maintainer) and Julie Josse (current maintainer).
The package includes:

- Parameters estimation.
- Estimation of standard deviation for estimated parameters.
- Model selection procedure based on BIC.

</br>
Reference:

<i><a href="https://www.sciencedirect.com/science/article/abs/pii/S0167947319302622?via%3Dihub">Logistic Regression with Missing Covariates – Parameter Estimation, Model Selection and Prediction (2020, Jiang W., Josse J., Lavielle M., TraumaBase Group), Computational Statistics & Data Analysis.</a></i>
