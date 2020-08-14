+++
# Project title.
title = "Bayesian Causal Inference"

# Date this page was created.
date = 2020-06-05T00:00:00

# Project summary to display on homepage.
summary = "Shrinkage, partial pooling, nonparametrics, and sensitivity analysis via priors - just some of the value Bayesian modeling can add to causal inference. "

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["causalbayes"]

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
  caption = "A causal dose-effect curve with an AR(1) prior that smooths the MLE."
  
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++

Causal inference is broadly concerned with estimating parameters governing the causal mechanisms between an intervention or treatment of interest and an outcome. Causal inference provides a framework for 1) constructing different estimands that have explicitly causal, rather than associational, interpretations 2) formulating the assumptions under which we can estimate these using observed data, 3) devising sensitivity analyses around violations of these assumptions, and 4) making valid inferences about these estimans. These are just some of the many advances made in the causal literature.

In practice, causal inference requires complex, high-dimensional models. Here, the Bayesian paradigm has a lot to offer. For instance, 

* **Shrinking** heterogeneous (stratum-specific) causal effects towards an overall average causal effect for sparse strata.
*  **Sparsity priors** such as Horseshoes and Spike-and-Slab that can regularize high-dimensional nuissance parameters. Such parameters are common in g-computation.
*  **Sensitivity Analyses** around causal identification assumptions. Uncertainty about the direction and magnitude of the bias can be expressed via a prior and baked into posterior inference.

See below for work related to Bayesian causal modeling.
