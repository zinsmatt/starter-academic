---
title: Level Set-Based Camera Pose Estimation From Multiple 2D/3D Ellipse-Ellipsoid Correspondences
authors:
- admin
- Gilles Simon
- Marie-Odile Berger
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2022-06-30"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-06-30"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Intelligent Robots and Systems (IROS 2022)*
publication_short: In *IROS*

abstract: In this paper, we propose an object-based camera pose estimation from a single RGB image and a pre-built map of objects, represented with ellipsoidal models. We show that contrary to point correspondences, the definition of a cost function characterizing the projection of a 3D object onto a 2D object detection is not straightforward. We develop an ellipse-ellipse cost based on level sets sampling, demonstrate its nice properties for handling partially visible objects and compare its performance with other common metrics, such as Intersection-over-Union, bounding box corners or Wasserstein distance. Finally, we show that the use of a predictive uncertainty on the detected ellipses allows a fair weighting of the contribution of the correspondences which improves the computed pose.



# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#008080">International Conference on Intelligent Robots and Systems (IROS 2022)</b><br> Camera pose refinement from objects by minimizing an ellipse-ellipse cost.
tags:
- Pose estimation
- Nonlinear optimization
- Ellipse-ellipse cost
- Uncertainty prediction
#- Source Themes
featured: true

links:
# - name: Open Access CVF
#   url: https://hal.inria.fr/hal-03602394
#   url_pdf: https://hal.inria.fr/hal-03602394/document
url_pdf: http://arxiv.org/abs/2207.07953
url_code: https://gitlab.inria.fr/tangram/level-set-based-camera-pose-estimation
#url_dataset: '#'
#url_poster: '#'
#url_project: 'https://blog.kitware.com/3d-reconstruction-from-satellite-images/'
#url_slides: ''
#url_source: '#'
url_video: 'https://youtu.be/TxtsvlMDxbM'

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

{{< youtube KXF4M3TvlJc >}}
