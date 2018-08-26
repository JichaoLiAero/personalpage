+++
title = "Adjoint Approach based on Reduced-order Model for Steady PDE Systems"
date = 2016-06-13T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Jichao Li", "K. Qu", "J. Cai", "C. Cao"]

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
publication = "*17th AIAA/ISSMO Multidisciplinary Analysis and Optimization Conference*"
publication_short = "*AIAA AVIATION*"

# Abstract and optional shortened version.
abstract = "An adjoint approach for the reduced-order model of steady PDE systems (adjoint ROM) is proposed to compute sensitivities derivatives. Firstly, a reduced-order model for the forward problem (forward ROM) is constructed, where Proper Orthogonal Decomposition (POD) is adopted. To meet the demand of general PDE systems, Petrov-Galerkin projection is adopted to solve the forward ROM. Afterwards, the adjoint ROM is constructed based on the POD-Petrov-Galerkin ROM. Due to the use of Petrov-Galerkin projection in solving the forward ROM, the formula of the adjoint ROM is rather complicated with system Hessian matrices brought in it. The cost of computing and storing these matrices might make it not worthwhile to compute sensitivities by this approach. In order to overcome this issue, a simplified formula of the adjoint ROM for general PDE problem is proposed with proper assumptions and omissions. Finally, numerical validations of the accuracy and efficiency by this adjoint ROM approach are presented with three cases, a quasi-one-dimensional nozzle flow case, an inviscid NACA0012 airfoil case and a viscous RAE2822 airfoil case. The results indicate that the computational cost by the adjoint ROM can be dramatically saved, and the sensitivities obtained by this approach are generally close to those computed by the traditional adjoint method."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = "datachord.png"

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
url_pdf = "https://arc.aiaa.org/doi/pdf/10.2514/6.2016-3668"
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
image = "datachord.png"
caption = ""

+++

