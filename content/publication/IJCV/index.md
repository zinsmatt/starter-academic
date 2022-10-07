---
title: Object-Based Visual Camera Pose Estimation From Ellipsoidal Model and 3D-Aware Ellipse Prediction
authors:
- admin
- Gilles Simon
- Marie-Odile Berger
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2022-02-01"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-02-01"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *International Journal of Computer Vision (IJCV)*
publication_short: In *IJCV*

abstract: In this paper, we propose a method for initial camera pose estimation from just a single image which is robust to viewing conditions and does not require a detailed model of the scene. This method meets the growing need of easy deployment of robotics or augmented reality applications in any environments, especially those for which no accurate 3D model nor huge amount of ground truth data are available. It exploits the ability of deep learning techniques to reliably detect objects regardless of viewing conditions. Previous works have also shown that abstracting the geometry of a scene of objects by an ellipsoid cloud allows to compute the camera pose accurately enough for various application needs. Though promising, these approaches use the ellipses fitted to the detection bounding boxes as an approximation of the imaged objects. In this paper, we go one step further and propose a learning-based method which detects improved elliptic approximations of objects which are coherent with the 3D ellipsoids in terms of perspective projection. Experiments prove that the accuracy of the computed pose significantly increases thanks to our method. This is achieved with very little effort in terms of training data acquisition -- a few hundred calibrated images of which only three need manual object annotation.

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#008080">International Journal of Computer Vision (IJCV)</b><br> Improve object-based visual localization by predicting 3D-aware ellipses. Extended work.
tags:
- Pose Estimation
- Deep Learning
- Ellipsoidal Model
#- Source Themes
featured: true

links:
- name: Open Access CVF
  url: https://hal.inria.fr/hal-03602394
  url_pdf: https://hal.inria.fr/hal-03602394/document
#url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
url_code: 'https://github.com/zinsmatt/3D-Aware-Ellipses-for-Visual-Localization'
#url_dataset: '#'
#url_poster: '#'
#url_project: 'https://blog.kitware.com/3d-reconstruction-from-satellite-images/'
#url_slides: ''
#url_source: '#'
#url_video: 'https://youtu.be/PhE4LzsqjAE'

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
slides: example
---


{{< youtube mGQ1tRELtlA >}}
