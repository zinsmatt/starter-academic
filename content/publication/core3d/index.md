---
title: "Urban Semantic 3D Reconstruction From Multiview Satellite Imagery"
authors:
- Matthew J. Leotta
- Chengjiang Long
- Bastien Jacquet
- admin
- Dan Lipsa
- Jie Shan
- Bo Xu
- Zhixin Li
- Xu Zhang
- Shih-Fu Chang
- Matthew Purri
- Jia Xue
- Kristin J. Dana
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2019-06-16"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-06-16"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Conference on Computer Vision and Pattern Recognition Workshops, CVPR 2019*
publication_short: In *CVPR Workshops 2019*

abstract: Methods for automated 3D urban modeling typically result in very dense point clouds or surface meshes derived from either overhead lidar or imagery (multiview stereo). Such models are very large and have no semantic separation of individual structures (i.e. buildings, bridges) from the terrain. Furthermore, such dense models often appear "melted" and do not capture sharp edges. This paper demonstrates an end-to-end system for segmenting buildings and bridges from terrain and estimating simple, low polygon, textured mesh models of these structures. The approach uses multiview-stereo satellite imagery as a starting point, but this work focuses on segmentation methods and regularized 3D surface extraction. Our work is evaluated on the IARPA CORE3D public data set using the associated ground truth and metrics. A web-based application deployed on AWS runs the algorithms and provides visualization of the results. Both the algorithms and web application are provided as open source software as a resource for further research or product development.

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#008080">CVPR Workshop 2019</b><br> Automatic system for 3D building reconstruction for the IARPA CORE3D program. <br><b style="color:#FF0000">This works received the Best Paper Award.</b>
tags:
#- Source Themes
featured: true

links:
- name: Open Access CVF
  url: https://openaccess.thecvf.com/content_CVPRW_2019/html/EarthVision/Leotta_Urban_Semantic_3D_Reconstruction_From_Multiview_Satellite_Imagery_CVPRW_2019_paper.html
  url_pdf: https://openaccess.thecvf.com/content_CVPRW_2019/papers/EarthVision/Leotta_Urban_Semantic_3D_Reconstruction_From_Multiview_Satellite_Imagery_CVPRW_2019_paper.pdf
#url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
url_code: 'https://github.com/Kitware/Danesfield'
#url_dataset: '#'
#url_poster: '#'
url_project: 'https://blog.kitware.com/3d-reconstruction-from-satellite-images/'
#url_slides: ''
#url_source: '#'
url_video: 'https://player.vimeo.com/video/321528248'

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


