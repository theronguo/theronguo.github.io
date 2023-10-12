---
title: "A reduced order model for geometrically parameterized two-scale simulations of elasto-plastic microstructures under large deformations"
authors:
- admin
- O. Rokos
- K. Veroy
author_notes:
- 
date: "2024-01-01T00:00:00Z"
doi: "10.1016/j.cma.2023.116467"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "*Computer Methods in Applied Mechanics and Engineering, 418A*(116467)*"
publication_short: ""

abstract: "In recent years, there has been a growing interest in understanding complex microstructures and their effect on macroscopic properties. In general, it is difficult to derive an effective constitutive law for such microstructures with reasonable accuracy and meaningful parameters. One numerical approach to bridge the scales is computational homogenization, in which a microscopic problem is solved at every macroscopic point, essentially replacing the effective constitutive model. Such approaches are, however, computationally expensive and typically infeasible in multi-query contexts such as optimization and material design. To render these analyses tractable, surrogate models that can accurately approximate and accelerate the microscopic problem over a large design space of shapes, material and loading parameters are required. In previous works, such models were constructed in a data-driven manner using methods such as Neural Networks (NN) or Gaussian Process Regression (GPR). However, these approaches currently suffer from issues, such as need for large amounts of training data, lack of physics, and considerable extrapolation errors. In this work, we develop a reduced order model based on Proper Orthogonal Decomposition (POD), Empirical Cubature Method (ECM) and a geometrical transformation method with the following key features: (i) large shape variations of the microstructure are captured, (ii) only relatively small amounts of training data are necessary, and (iii) highly non-linear history-dependent behaviors are treated. The proposed framework is tested and examined in two numerical examples, involving two scales and large geometrical variations. In both cases, high speed-ups and accuracies are achieved while observing good extrapolation behavior."

# Summary. An optional shortened abstract.
summary:

tags:
- reduced order modelling
- proper orthogonal decomposition
- computational homogenization
- hyperreduction
- empirical cubature method
- geometrical transformation
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


