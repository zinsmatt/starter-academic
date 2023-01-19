---
title: "OA-SLAM: Leveraging Objects for Camera Relocalization in Visual SLAM"
authors:
- admin
- Gilles Simon
- Marie-Odile Berger
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2022-08-16"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-08-16"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Symposium on Mixed and Augmented Reality (ISMAR 2022)*
publication_short: In *ISMAR*

abstract: \[AR Demo https://youtu.be/PXG_6LkbtgY\] In this work, we explore the use of objects in Simultaneous Localization and Mapping in unseen worlds and propose an object-aided system (OA-SLAM). More precisely, we show that, compared to low-level points, the major benefit of objects lies in their higher-level semantic and discriminating power. Points, on the contrary, have a better spatial localization accuracy than the generic coarse models used to represent objects (cuboid or ellipsoid). We show that combining points and objects is of great interest to address the problem of camera pose recovery. Our main contributions are (1) we improve the relocalization ability of a SLAM system using high-level object landmarks; (2) we build an automatic system, capable of identifying, tracking and reconstructing objects with 3D ellipsoids; (3) we show that object-based localization can be used to reinitialize or resume camera tracking. Our fully automatic system allows on-the-fly object mapping and enhanced pose tracking recovery, which we think, can significantly benefit to the AR community. Our experiments show that the camera can be relocalized from viewpoints where classical methods fail. We demonstrate that this localization allows a SLAM system to continue working despite a tracking loss, which can happen frequently with an uninitiated user.



# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#008080">International Symposium on Mixed and Augmented Reality (ISMAR 2022)</b><br> \[AR Demo https://youtu.be/PXG_6LkbtgY\] Object-based SLAM with on-the-fly object mapping and improved camera relocalization.
tags:
- Visual SLAM
- Object mapping
- Camera relocalization
#- Source Themes
featured: true

links:
# - name: Open Access CVF
#   url: https://hal.inria.fr/hal-03602394
#   url_pdf: https://hal.inria.fr/hal-03602394/document
url_pdf: https://arxiv.org/abs/2209.08338
url_code: https://gitlab.inria.fr/tangram/oa-slam
#url_dataset: '#'
#url_poster: '#'
#url_project: 'https://blog.kitware.com/3d-reconstruction-from-satellite-images/'
#url_slides: ''
#url_source: '#'
url_video: 'https://youtu.be/L1HEL4kLJ3g'
# url_poster: 'https://youtu.be/L1HEL4kLJ3g'

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

{{< youtube L1HEL4kLJ3g >}}
