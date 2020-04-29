---
title: "Improving Multimodal Object Detection with Individual Sensor Monitoring"
authors:
- Christopher Kuhn
- admin
- Goran Petrovic
- Eckehard Steinbach
date: "2022-12-05T00:00:00Z"
doi: "10.1109/ISM55400.2022.00022"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-10-27T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *24nd IEEE International Symposium on Multimedia*
publication_short: In *ISM2022*

abstract: "Multimodal object detection fuses different sensors such as camera or LIDAR to improve the detection performance. However, individual sensor inputs can also be detrimental to a system, for example when sun glare hits a camera. In this work, we propose to monitor each sensor individually to predict when an input would lead to incorrect detections. We first train one detection network for each sensor separately, using only that sensor as input. Then, we record the performance for each single-sensor network and train an introspective performance prediction network for each sensor. Finally, we train a multimodal fusion network where we weight the impact of each sensor with its predicted performance. This allows us to dynamically adapt the fusion to reduce the influence of harmful sensor readings based only on the current data. We apply the proposed concept to the state-of-the-art AVOD architecture and evaluate on the KITTI data set. The proposed sensor monitoring system improves the mean intersection-over-union performance by 4.6%. For inputs with a low predicted performance, the proposed approach outperforms the state of the art by over 10%, demonstrating the potential of using individual sensor monitoring to react to problematic input. The proposed approach can be applied to any fusion network with two or more sensors and could also be used for classification or segmentation tasks."

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
  url: https://doi.org/10.1109/ISM55400.2022
url_pdf: "https://www.researchgate.net/publication/364997356_Improving_Multimodal_Object_Detection_with_Individual_Sensor_Monitoring"
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://www.researchgate.net/project/Failure-Prediction-in-Autonomous-Driving'
url_slides: 'https://docs.google.com/presentation/d/1CeOhdl0I_YW-mMnisWH9cBCpxO3u5BN-/edit'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**IEEE**](https://doi.org/10.1109/ISM55400.2022.00022)'
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
