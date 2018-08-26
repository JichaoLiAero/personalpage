+++
title = "Surrogate-based aerodynamic shape optimization with the active subspace method"
date = 2018-08-11T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Jichao Li", "J. Cai", "K, Qu"]

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
publication = "*Structural and Multidisciplinary Optimization*"
publication_short = "*Structural and Multidisciplinary Optimization*"

# Abstract and optional shortened version.
abstract = "Surrogate-based optimization is criticized in high-dimensional cases because it cannot scale well with the input dimension. In order to overcome this issue, we adopt a snapshot active subspace method to reduce the input dimension. A smoothing operation of samples is used to reduce the demand for snapshots in the construction of active subspaces. This operation significantly reduces the computational cost on the one hand, and on the other hand, it leads to more feasible subspaces. We use a 90% ∼ 95% energy coverage criterion to define the dimension of the subspace. With this criterion, the surrogate-based airfoil optimization in the active subspace is both efficient and effective. We also validate this optimization approach in an ONERA M6 wing optimization case with 220 shape variables. Compared with original surrogate-based optimization, the new approach reduces the computational time by 70% and obtains a more practical design with a smaller drag."
abstract_short = "This paper presents a method coupling surrogate-based optimization with the active subspace method (ASM-SBO), which protects high-dimensional aerodynamic shape optimization from the [curse of dimensionality](https://en.wikipedia.org/wiki/Curse_of_dimensionality)."

# Featured image thumbnail (optional)
image_preview = "ASM_3D_history.png"

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
image = "ASM_3D.png"
caption = "Wing shape deformations corresponding to different ASM vectors"

+++

