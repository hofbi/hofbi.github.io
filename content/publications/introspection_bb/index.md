---
title: "Introspective Black Box Failure Prediction for Autonomous Driving"
authors:
- Christopher Kuhn
- admin
- Goran Petrovic
- Eckehard Steinbach
date: "2020-10-20T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-04-20T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *31st IEEE Intelligent Vehicles Symposium*
publication_short: In *IV2020*

abstract: "Failures in autonomous driving caused by complex traffic situations or model inaccuracies remain inevitable in the near future. While much research is focused on how to prevent such failures, comparatively little research has been done on predicting them. An early failure prediction would allow for more time to take actions to resolve challenging situations. In this work, we propose an introspective approach to predict future disengagements of the car by learning from previous disengagement sequences. Our method is designed to detect failures as early as possible by using sensor data from up to ten seconds before each disengagement. The car itself is treated as a black box, with only its state data and the number of detected objects being required. Since no model-specific knowledge is needed, our method is applicable to any self-driving system. Currently, no public data of real-life disengagements is available. To test our approach, we therefore use autonomous driving data provided by BMW that was collected with BMW research vehicles over three months. We show that an LSTM classifier trained with sequences of state data can predict failures up to seven seconds in advance with an accuracy of more than 80%. This is two seconds earlier than comparable approaches from the literature."

# Summary. An optional shortened abstract.
summary: ""

tags:
- Failure Prediction
- Autonomous Driving
featured: false

hugoblox:
  ids:
    doi: "10.1109/IV47402.2020.9304844"

links:
- type: custom
  label: Conference
  url: https://2020.ieee-iv.org/
- type: custom
  label: Proceedings
  url: https://doi.org/10.1109/IV47402.2020
- type: pdf
  url: https://www.researchgate.net/publication/341293627_Introspective_Black_Box_Failure_Prediction_for_Autonomous_Driving
- type: poster
  url: https://drive.google.com/file/d/1-Ah37PNr8kDRnKWgNVHxQkETx8YNTkWx/view
- type: project
  url: https://www.researchgate.net/project/Failure-Prediction-in-Autonomous-Driving
- type: slides
  url: https://drive.google.com/file/d/1ynPSgjqBVjibgS-OI_Tnsd9JS7RNvmWE/view
- type: video
  url: https://youtu.be/rWQvFTvB-ks

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**IEEE**](https://doi.org/10.1109/IV47402.2020.9304844)'
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
