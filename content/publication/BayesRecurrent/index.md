+++
title = "A Bayesian Framework for Causal Analysis of Recurrent Events with Timing Misalignment"
date = 2024-11-15T00:00:00

# Authors. Comma separated list, e.g.
authors = ["A. Oganisian", "A. Girard", "JA. Steingrimsson", "P. Moyo"]

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
publication_short = "*Biometrics*"

# Abstract.
abstract = "Observational studies of recurrent event rates are common in biomedical statistics. Broadly, the goal is to estimate differences in event rates under two treatments within a defined target population over a specified followup window. Estimation with observational data is challenging because, while membership in the target population is defined in terms of eligibility criteria, treatment is rarely observed exactly at the time of eligibility. Ad-hoc solutions to this timing misalignment can induce bias by incorrectly attributing prior event counts and person-time to treatment. Even if eligibility and treatment are aligned, a terminal event process (e.g. death) often stops the recurrent event process of interest. In practice, both processes can be censored so that events are not observed over the entire followup window. Our approach addresses misalignment by casting it as a time-varying treatment problem: some patients are on treatment at eligibility while others are off treatment but may switch to treatment at a specified time - if they survive long enough. We define and identify an average causal effect estimand under right-censoring. Estimation is done using a g-computation procedure with a joint semiparametric Bayesian model for the death and recurrent event processes. We apply the method to contrast hospitalization rates among patients with different opioid treatments using Medicare insurance claims data."

# Summary. An optional shortened abstract.
summary = " "

# Digital Object Identifier (DOI)
doi = "10.1093/biomtc/ujae145"

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
url_pdf = "#"
url_preprint = "https://arxiv.org/abs/2304.03247"
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
  caption = "Bayesian semiparametric baseline hazard (left) and event rate (right) under gAR1 smoothing priors."

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Center"
+++
