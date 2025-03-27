+++
title = "Bayesian Causal Inference with Recurrent Event Outcomes"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date = 2025-03-24T15:05:00
#date_end = 2018-07-31T15:25:00
all_day = true

# Schedule page publish date (NOT talk date).
publishDate = []

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Arman Oganisian"]

# Location of event.
location = "New Orleans, LA"

# Name of event and optional event URL.
event = "Eastern North American Region (ENAR) Meeting 2025"

# Abstract. What's your talk about?
#abstract = "Observational studies of recurrent event rates are common in biomedical statistics. Broadly, the goal is to estimate differences in event rates under two treatments within a defined target population over a specified followup window. Estimation with observational data is challenging because, while membership in the target population is defined in terms of eligibility criteria, treatment is rarely observed exactly at the time of eligibility. Ad-hoc solutions to this timing misalignment can induce bias by incorrectly attributing prior event counts and person-time to treatment. Even if eligibility and treatment are aligned, a terminal event process (e.g. death) often stops the recurrent event process of interest. In practice, both processes can be censored so that events are not observed over the entire followup window. Our approach addresses misalignment by casting it as a time-varying treatment problem: some patients are on treatment at eligibility while others are off treatment but may switch to treatment at a specified time - if they survive long enough. We define and identify an average causal effect estimand under right-censoring. Estimation is done using a g-computation procedure with a joint semiparametric Bayesian model for the death and recurrent event processes. We apply the method to contrast hospitalization rates among patients with different opioid treatments using Medicare insurance claims data."

# Summary. An optional shortened abstract.
summary = "Talk presented at ENAR 2025."

# Is this a featured talk? (true/false)
featured = false

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides = "example-slides"

# Optional filename of your slides within your talk folder or a URL.
url_slides = "Oganisian_RecurrentEvents.pdf"

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["bnp","causalbayes"]

# Links (optional).
url_pdf = ""
url_video = ""
url_code = ""

# Demo talk page uses LaTeX math.
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Posterior inference for temporally smoothed discrete-time hazard of death."

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Center"
+++

