---
title: "Learning constitutive models from microstructural simulations via a non-intrusive reduced basis method"
authors:
- admin
- Ondrej Rokos
- Karen Veroy
author_notes:
- 
date: "2021-10-01T00:00:00Z"
doi: "10.1016/j.cma.2021.113924"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Computer Methods in Applied Mechanics and Engineering, 384*(113924)"
publication_short: ""

abstract: "In order to optimally design materials, it is crucial to understand the structure–property relations in the material by analyzing the effect of microstructure parameters on the macroscopic properties. In computational homogenization, the microstructure is thus explicitly modeled inside the macrostructure, leading to a coupled two-scale formulation. Unfortunately, the high computational costs of such multiscale simulations often render the solution of design, optimization, or inverse problems infeasible. To address this issue, we propose in this work a non-intrusive reduced basis method to construct inexpensive surrogates for parametrized microscale problems; the method is specifically well-suited for multiscale simulations since the coupled simulation is decoupled into two independent problems: (1) solving the microscopic problem for different (loading or material) parameters and learning a surrogate model from the data; and (2) solving the macroscopic problem with the learned material model. The proposed method has three key features. First, the microscopic stress field can be fully recovered, which is useful for instance for revealing local stress concentrations inside the microstructure. Second, the method is able to accurately predict the stress field for a wide range of material parameters; furthermore, the derivatives of the effective stress with respect to the material parameters are available and can be readily utilized in solving optimization problems. Finally, it is more data efficient, i.e. requiring less training data, as compared to directly performing a regression on the effective stress. To construct the surrogate model, first, a proper orthogonal decomposition is performed on precomputed microscopic stress field snapshots to find a reduced basis for the stress. Second, a regression is employed to infer the coefficients of the reduced basis approximation for any arbitrary parameter value, thus enabling a rapid online evaluation of the microscopic stress. Equipped with the stress field, the effective stress and its partial derivatives can then be derived analytically. For the microstructures in the two test problems considered, the mean approximation error of the effective stress is as low as 0.1% despite using a relatively small training dataset. Embedded into the macroscopic problem, the reduced order model leads to an online computational speed up of approximately three orders of magnitude while maintaining a high accuracy as compared to the FE² solver."

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Proper Orthogonal Decomposition
- Gaussian Process Regression
- Computational Homogenization
- Constitutive Modeling
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: 
---
