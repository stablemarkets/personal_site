+++
# Project title.
title = "Non-parametric Bayes"

# Date this page was created.
date = 2020-07-10T00:00:00

# Project summary to display on homepage.
summary = "Bayesian modeling - flexiblilty, uncertainty quantification, full posterior inference."

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["bnp"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides = "example-slides"

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#links = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com/georgecushen"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
[image]
  # Caption (optional)
  caption = "Posterior regression line/band from Gaussian process regression."
  
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++

Bayesian nonparametrics is a powerful class of methods including Gaussian processes, Bayesian Additive Regression Trees (BART), Gamma Processes, Dirichlet Process, etc. The central idea is to abstract away from parameters. For instance, standard methods may assume a regression function is linear, indexed by finitely many slope/intercept parameters. A prior on these finitely many parameters then induces a prior on the regression function. To avoid specifying such restrictive functional form, we need to cut out the middle-man (the parameters) and specify priors over the function *directly*. Bayesian nonparametrics is characterized by priors over such abstract objects: priors over regressions, priors over baseline hazard functions, prior distributions over distributions themselves. 

These methods give you the flexibility of machine learning, with the added benefit uncertainty quantitification via full posterior inference. 

See below for work related to nonparametric Bayesian inference.