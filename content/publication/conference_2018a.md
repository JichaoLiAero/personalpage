+++
title = "A data-based approach for fast airfoil analysis and optimization"
date = 2018-01-08T00:00:00
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
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "*2018 AIAA/ASCE/AHS/ASC Structures, Structural Dynamics, and Materials Conference*"
publication_short = "*AIAA SciTech*"

# Abstract and optional shortened version.
abstract = "Airfoils are of great importance in aerodynamic design, and there is a need for tools that can evaluate and optimize their performance. Existing tools are usually either accurate or efficient, but not both. This paper presents a tool that can analyze airfoils in both subsonic and transonic regimes in about one hundredth of a second, and optimize airfoil shapes in a few seconds. We use camber and thickness mode shapes derived from over one thousand existing airfoils to parameterize the airfoil shape, which reduces the number of design variables. More than one hundred thousand RANS evaluations associated with different airfoils and flow conditions (M, AoA) are selected in a well-defined way to obtain aerodynamic coefficients ($C_l$, $C_d$ and $C_m$) and their gradients. The gradients for the RANS evaluations are computed using an adjoint method. This data is used to train a surrogate model that combines gradient-enhanced kriging, partial least squares (GE-KPLS), and mixture of experts. Two global models composed of dozens of GE-KPLS models are constructed in the subsonic and transonic regimes. These surrogate models provide fast aerodynamic analysis and gradient computation, which are coupled with a gradient-based optimizer to perform rapid airfoil shape design optimization. In a validating test of 2741 airfoils and 989 airfoils in the subsonic and transonic regimes, the mean differences of the surrogate models from RANS evaluations in the drag coefficient are 0.09 and 0.8 counts, respectively. We also validate the airfoil optimization for various cases by comparing with drag minimization based on direct RANS analysis. The largest differences in Cd are 0.04 counts for subsonic cases, and 2.5 counts for transonic cases. This approach opens the door for interactive airfoil analysis and design using any modern computer or mobile device."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = "airfoil_opt.png"

# Is this a selected publication? (true/false)
selected = false

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
url_pdf = "https://arc.aiaa.org/doi/pdf/10.2514/6.2018-1383"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = "https://www.researchgate.net/publication/322869846_A_Data-based_Approach_for_Fast_Airfoil_Analysis_and_Optimization"
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
image = "airfoil_opt.png"
caption = "Multipoint optimization in the transonic regime"

+++

