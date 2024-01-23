+++
title = "Hierarchical Bayesian Bootstrap for Heterogeneous Treatment Effect Estimation"
date = 2022-12-22T00:00:00

authors = ["A. Oganisian","Nandita Mitra", "Jason Roy"]

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
publication = "*International Journal of Biostatistics*"
publication_short = "*International Journal of Biostatistics*"

# Abstract.
abstract = "A major focus of causal inference is the estimation of heterogeneous average treatment effects (HTE) - average treatment effects within strata of another variable of interest such as levels of a biomarker, education, or age strata. Inference involves estimating a stratum-specific regression and integrating it over the distribution of confounders in that stratum - which itself must be estimated. Standard practice involves estimating these stratum-specific confounder distributions independently (e.g. via the empirical distribution or Rubin's Bayesian bootstrap), which becomes problematic for sparsely populated strata with few observed confounder vectors. In this paper, we develop a nonparametric hierarchical Bayesian bootstrap (HBB) prior over the stratum-specific confounder distributions for HTE estimation. The HBB partially pools the stratum-specific distributions, thereby allowing principled borrowing of confounder information across strata when sparsity is a concern. We show that posterior inference under the HBB can yield efficiency gains over standard marginalization approaches while avoiding strong parametric assumptions about the confounder distribution. We use our approach to estimate the adverse event risk of proton versus photon chemoradiotherapy across various cancer types."

# Summary. An optional shortened abstract.
summary = ""

# Digital Object Identifier (DOI)
doi = ""

# Is this a featured publication? (true/false)
featured = true

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["causalbayes", "bnp"]

# Links (optional).
url_pdf = "https://www.degruyter.com/document/doi/10.1515/ijb-2022-0051/html?lang=en"
url_preprint = "https://arxiv.org/abs/2009.10839"
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
  caption = "One realization of three correlated distributions from the hierarchical Bayesian bootstrap prior."

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
