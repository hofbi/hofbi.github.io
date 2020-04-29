---
title: "Reverse Error Modeling for Improved Semantic Segmentation"
authors:
- Christopher Kuhn
- me
- Goran Petrovic
- Eckehard Steinbach
date: "2022-10-16T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-06-23T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *29th IEEE International Conference on Image Processing*
publication_short: In *ICIP2022*

abstract: "We propose the concept of error-reversing autoencoders (ERA) for correcting pixel-wise errors made by an arbitrary semantic segmentation model. For this, we reframe the segmentation model as an error function applied to the ground truth labels. Then, we train an autoencoder to reverse this error function. During testing, the autoencoder reverses the approximated error function to correct the classification errors. We consider two sources of errors. First, we target the errors made by a model despite having being trained with clean, accurately labeled images. In this case, our proposed approach achieves an improvement of around 1% on the Cityscapes data set with the state-of-the-art DeepLabV3+ model. Second, we target errors introduced by compromised images. With JPEG-compressed images as input, our approach improves the segmentation performance by over 70% for high levels of compression. The proposed architecture is simple to implement, fast to train and can be applied to any semantic segmentation model as a post-processing step."

# Summary. An optional shortened abstract.
summary: ""

tags:
- Image Processing
- Failure Prediction
- Semantic Segmentation
featured: false

hugoblox:
  ids:
    doi: "10.1109/ICIP46576.2022.9897331"

links:
- type: custom
  label: Conference
  url: https://2022.ieeeicip.org/
- type: custom
  label: Proceedings
  url: https://doi.org/10.1109/ICIP46576.2022
- type: pdf
  url: "https://www.researchgate.net/publication/362889594_Reverse_Error_Modeling_for_Improved_Semantic_Segmentation"
- type: project
  url: 'https://www.researchgate.net/project/Failure-Prediction-in-Autonomous-Driving'
- type: slides
  url: 'https://docs.google.com/presentation/d/1QzQ44n_WxyceQeWzeyLWMBWCVjxik3Fl/edit'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**IEEE**](https://doi.org/10.1109/ICIP46576.2022.9897331)'
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
