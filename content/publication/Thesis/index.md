---
title: Contributions to the accuracy and robustness of visual localization in a world of objects
authors:
- admin
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2022-12-09"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-12-09"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: Thesis manuscript
publication_short: Thesis manuscript

abstract: \[[Examinators report](/files/Thesis_reports_examinators.pdf)\] Visual localization is a well-known problem in computer vision, which has many applications, for example, in robotics for autonomous navigation (robots, drones, vehicles) or in augmented reality. It consists in estimating the position and orientation of the camera in a scene. Classical approaches are generally based on the geometric structure of the scene and seek to match 2D keypoints, detected in the images, with 3D points of the scene. This matching is however a complex problem in practice, especially because it relies on local information, extracted in the neighborhood of the keypoints. Depending on the size of the scene, these methods can be very computationally expensive. They are also sensitive to large changes in viewpoints, to degraded visual conditions and fail in weakly textured areas. In this thesis, we are interested in using objects as semantic landmarks for visual positioning. Thanks to recent advances, especially with deep learning, it is possible to detect objects very robustly in images, from almost any viewpoint. We have adopted a lightweight modeling of objects as ellipsoids and want to leverage this to improve the robustness of visual localization. As a first step, we sought to improve the detection of objects by ellipsoids, which was one of the main sources of inaccuracy in the pose computation. Thus, we replaced the ellipses inscribed in the detection boxes aligned with the image axes by oriented ellipses consistent with the projection of the ellipsoidal models of the objects. Our experiments have shown that our approach significantly improves the accuracy of existing object-based methods and outperforms the robustness of point-based methods. Secondly, we proposed a refinement step of the camera pose by minimizing a reprojection error, which allows us to take into account all the detected objects in the image. Unlike a distance between points, establishing a cost between ellipses is not trivial. We analyzed different metrics and proposed a new formulation based on level sets. Our experiments highlighted its good convergence properties and a better handling of partially visible objects in the image. We have also shown that this refinement step allows us to considerably improve the analytical solution of the object-based pose calculation. Finally, we integrated this concept of object into SLAM and developed a system capable of mapping objects on the fly. The interest is twofold, with the possibility to use them as relocalization landmarks and with the introduction of semantic information in the map, offering a better scene understanding. Our system makes objects and points collaborate and benefits from their respective advantages, robustness and accuracy. We have shown, in our experiments, that this allows us to significantly extend the relocalization capability of our system.

# Summary. An optional shortened abstract.
summary: <b style="font-size:120%;color:#008080">Thesis manuscript</b></br> [Examinators report](/files/Thesis_reports_examinators.pdf)

tags:
- Visual Localization
- Semantic SLAM
- Ellipsoidal Model
#- Source Themes
featured: true

links:
# - name: Open Access CVF
  # url: https://hal.inria.fr/hal-03602394
url_pdf: https://hal.archives-ouvertes.fr/tel-03922962/document
#url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
url_code: https://gitlab.inria.fr/tangram
url_video: these/
#url_dataset: '#'
#url_poster: '#'
#url_project: 'https://blog.kitware.com/3d-reconstruction-from-satellite-images/'
#url_slides: ''
#url_source: '#'

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

