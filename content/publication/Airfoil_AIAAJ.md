+++
title = "Data-based Approach for Fast Airfoil Analysis and Optimization"
date = 2018-08-06T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Jichao Li", "M. A. Bouhlel", "J. R. R. A. Martins"]

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
abstract = "Airfoils are of great importance in aerodynamic design, and various tools have been developed to evaluate and optimize their performance. Existing tools are usually either accurate or efficient, but not both. This paper presents a tool that can analyze airfoils in both subsonic and transonic regimes in about one hundredth of a second, and optimize airfoil shapes in a few seconds. We use camber and thickness mode shapes derived from over one thousand existing airfoils to parameterize the airfoil shape, which reduces the number of design variables. More than one hundred thousand RANS evaluations associated with different airfoils and flow conditions are used to train a surrogate model that combines gradient-enhanced kriging, partial least squares, and mixture of experts. These surrogate models provide fast aerodynamic analysis and gradient computation, which are coupled with a gradient-based optimizer to perform rapid airfoil shape design optimization. When comparing the surrogate-based optimization with optimization based on direct RANS evaluations, the largest differences in minimum $C_d$ are 0.04 counts for subsonic cases and 2.5 counts for transonic cases. This approach opens the door for interactive airfoil analysis and design optimization using any modern computer or mobile device."
abstract_short = "This paper presents a data-based approach that can analyze almost all airfoils in both subsonic and transonic regimes in about 0.001 second, and optimize airfoil shapes in about 1 second."

# Featured image thumbnail (optional)
image_preview = "airfoils.jpg"

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
url_pdf = ""
url_preprint = ""
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
image = "airfoils.jpg"
caption = "Camber-thickness shape modes fits thickness constraints in arifoil shape optimization"

+++

