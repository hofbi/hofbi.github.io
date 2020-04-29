---
title: "Better Look Twice - Improving Visual Scene Perception Using a Two-Stage Approach"
authors:
- Christopher Kuhn
- admin
- Goran Petrovic
- Eckehard Steinbach
date: "2020-12-02T00:00:00Z"
doi: "10.1109/ISM.2020.00013"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-11-09T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *22nd IEEE International Symposium on Multimedia*
publication_short: In *ISM2020*

abstract: "Accurate visual scene perception plays an important role in fields such as medical imaging or autonomous driving. Recent advances in computer vision allow for accurate image classification, object detection and even pixel-wise semantic segmentation. Human vision has repeatedly been used as an inspiration for developing new machine vision approaches. In this work, we propose to adapt the \"zoom lens model\" from psychology for semantic scene segmentation. According to this model, humans first distribute their attention evenly across the entire field of view at low processing power. Then, they follow visual cues to look at a few smaller areas with increased attention. By looking twice, it is possible to refine the initial scene understanding without requiring additional input. We propose to perform semantic segmentation the same way. To obtain visual cues for deciding where to look twice, we use a failure region prediction approach based on a state-of-the-art failure prediction method. Then, the second, focused look is performed by a dedicated classifier that reclassifies the most challenging patches. Finally, pixels predicted to be errors are updated in the original semantic prediction. While focusing only on areas with the highest predicted failure probability, we achieve a classification accuracy of over 63% for the predicted failure regions. After updating the initial semantic prediction of 4000 test images from a large-scale driving data set, we reduce the absolute pixel-wise error of 232 road participants by 10% or more."

# Summary. An optional shortened abstract.
summary: ""

tags:
- Computer Vision
- Failure Prediction
featured: false

links:
- name: Conference
  url: https://www.ieee-ism.org/
- name: Proceedings
  url: https://doi.org/10.1109/ISM50513.2020
- name: Award
  url: https://www.ei.tum.de/en/lmt/news/article/best-student-paper-award-auf-der-ism-2020/
url_pdf: "https://www.researchgate.net/publication/345389376_Better_Look_Twice_-Improving_Visual_Scene_Perception_Using_a_Two-Stage_Approach"
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://www.researchgate.net/project/Failure-Prediction-in-Autonomous-Driving'
url_slides: 'https://drive.google.com/file/d/1nqmQLQCwXR8WFSLiPyAJEfvBCe52CQJm/view'
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
projects:
- research

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
