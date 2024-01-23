+++
title = "Bayesian Nonparametric Method for Zero-Inflated Outcomes: Prediction, Clustering, and Causal Inference"
date = 2020-02-01T00:00:00

# Authors. Comma separated list, e.g. `["Arman Oganisian", "Nandita Mitra", "Jason Roy"]`.
authors = ["A. Oganisian", "Nandita Mitra", "Jason Roy"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "*Biometrics*"
publication_short = ""

# Abstract.
abstract = "Researchers are often interested in predicting outcomes, detecting distinct subgroups of their data, or estimating causal treatment effects. Pathological data distributions that exhibit skewness and zero-inflation complicate these tasks—requiring highly flexible, data-adaptive modeling. In this paper, we present a multipurpose Bayesian nonparametric model for continuous, zero-inflated outcomes that simultaneously predicts structural zeros, captures skewness, and clusters patients with similar joint data distributions. The flexibility of our approach yields predictions that capture the joint data distribution better than commonly used zero-inflated methods. Moreover, we demonstrate that our model can be coherently incorporated into a standardization procedure for computing causal effect estimates that are robust to such data pathologies. Uncertainty at all levels of this model flow through to the causal effect estimates of interest—allowing easy point estimation, interval estimation, and posterior predictive checks verifying positivity, a required causal identification assumption. Our simulation results show point estimates to have low bias and interval estimates to have close to nominal coverage under complicated data settings. Under simpler settings, these results hold while incurring lower efficiency loss than comparator methods. We use our proposed method to analyze zero-inflated inpatient medical costs among endometrial cancer patients receiving either chemotherapy or radiation therapy in the SEER-Medicare database."

# Summary. An optional shortened abstract.
summary = ""

# Digital Object Identifier (DOI)
doi = ""

# Is this a featured publication? (true/false)
featured = false

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["bnp","causalbayes"]

# Links (optional).
url_pdf = "https://onlinelibrary.wiley.com/doi/abs/10.1111/biom.13244"
url_preprint = "https://arxiv.org/abs/1810.09494"
#url_code = "#"
#url_dataset = "#"
#url_project = ""
#url_slides = "#"
#url_video = "#"
#url_poster = "#"
#url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#links = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Predictions from zero-inflated Dirichlet process mixture"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
