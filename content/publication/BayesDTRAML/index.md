+++
title = "Bayesian Semiparametric Model for Sequential Treatment Decisions with Informative Timing"
date = 2022-11-01T00:00:00

# Authors. Comma separated list, e.g.
authors = ["A. Oganisian", "K. Getz", "T. Alonzo", "R. Aplenc", "J. Roy"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["3"]

# Publication name and optional abbreviated version.
publication = "*arXiv*"
publication_short = ""

# Abstract.
abstract = "We develop a Bayesian semi-parametric model for the estimating the impact of dynamic treatment rules on survival among patients diagnosed with pediatric acute myeloid leukemia (AML). The data consist of a subset of patients enrolled in the phase III AAML1031 clinical trial in which patients move through a sequence of four treatment courses. At each course, they undergo treatment that may or may not include anthracyclines (ACT). While ACT is known to be effective at treating AML, it is also cardiotoxic and can lead to early death for some patients. Our task is to estimate the potential survival probability under hypothetical dynamic ACT treatment strategies, but there are several impediments. First, since ACT was not randomized in the trial, its effect on survival is confounded over time. Second, subjects initiate the next course depending on when they recover from the previous course, making timing potentially informative of subsequent treatment and survival. Third, patients may die or drop out before ever completing the full treatment sequence. We develop a generative Bayesian semi-parametric model based on Gamma Process priors to address these complexities. At each treatment course, the model captures subjects' transition to subsequent treatment or death in continuous time under a given rule. A g-computation procedure is used to compute a posterior over potential survival probability that is adjusted for time-varying confounding. Using this approach, we conduct posterior inference for the efficacy of hypothetical treatment rules that dynamically modify ACT based on evolving cardiac function."

# Summary. An optional shortened abstract.
summary = " "

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
#url_preprint = "#"
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
  caption = "Posterior survival curves under two different dynamic treatment rules and their ratio contrasts"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Center"
+++
