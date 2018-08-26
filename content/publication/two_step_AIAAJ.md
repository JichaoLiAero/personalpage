+++
title = "Adjoint-Based Two-Step Optimization Method Using Proper Orthogonal Decomposition and Domain Decomposition"
date = 2018-01-31T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Jichao Li", "J. Cai", "K. Qu"]

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
publication = "*AIAA Journal*"
publication_short = "*AIAA Journal*"

# Abstract and optional shortened version.
abstract = "A modified two-step method for aerodynamic shape optimization is proposed, where proper orthogonal decomposition and automatic domain-decomposition techniques are adopted to accelerate flow and adjoint solutions in the second-step optimization. As the first step in this method, the initial optimization is first performed by a genetic algorithm coupled with a kriging model. Next, a reduced-order model is set up via proper orthogonal decomposition with the reuse of ready-made flow snapshots in the first-step optimization. A proper-orthogonal-decomposition Petrov-Galerkin method is investigated to provide fast flow predictions in the second-step optimization. With the assistance of an error estimation method and an automatic domain-decomposition method that are presented in this paper, the sensitive domain in the computational grid is split out. To improve the accuracy, predictions provided by proper orthogonal decomposition in the sensitive domain are further corrected by computational fluid dynamics modifications. Meanwhile, in order to accelerate gradient solutions, the adjoint equation of this proper orthogonal decomposition and domain-decomposition-based flow analysis method is derived and discussed. The optimization results of a two-dimensional airfoil design test and a three-dimensional wing design test highlight the efficiency of the proposed method when compared with results of either a gradient-free optimization method or a traditional two-step method."
abstract_short = "This paper presents a modified two-step method for aerodynamic shape optimization. The modifications with POD and domain decomposition techniques accelarte CFD simulations and adjoint solutions in the second-step optimization."

# Featured image thumbnail (optional)
image_preview = "two_step.png"

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's filename without extension.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "https://arc.aiaa.org/doi/pdf/10.2514/1.J055773"
url_preprint = "https://www.researchgate.net/publication/322907770_Adjoint-Based_Two-Step_Optimization_Method_Using_Proper_Orthogonal_Decomposition_and_Domain_Decomposition"
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = true

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "two_step_error.png"
caption = "Predication error of two POD approaches"

+++

