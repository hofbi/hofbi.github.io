---
title: "Trajectory-Based Failure Prediction for Autonomous Driving"
authors:
- Christopher Kuhn
- me
- Goran Petrovic
- Eckehard Steinbach
date: "2021-07-11T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-05-30T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *32st IEEE Intelligent Vehicles Symposium*
publication_short: In *IV2021*

abstract: "In autonomous driving, complex traffic scenarios can cause situations that require human supervision to resolve safely. Instead of only reacting to such events, it is desirable to predict them early in advance. While predicting the future is challenging, there is a source of information about the future readily available in autonomous driving: the planned trajectory the car intends to drive. In this paper, we propose to analyze the trajectories planned by the vehicle to predict failures early on. We consider sequences of trajectories and use machine learning to detect patterns that indicate impending failures. Since no public data of disengagements of autonomous vehicles is available, we use data provided by development vehicles of the BMW Group. From over six months of test drives, we obtain more than 2600 disengagements of the automated system. We train a Long Short-Term Memory classifier with sequences of planned trajectories that either resulted in successful driving or disengagements. The proposed approach outperforms existing state-of-the-art failure prediction with low-dimensional data by more than 3% in a Receiver Operating Characteristic analysis. Since our approach makes no assumptions on the underlying system, it can be applied to predict failures in other safety-critical areas of robotics as well."

# Summary. An optional shortened abstract.
summary: ""

tags:
- Failure Prediction
- Autonomous Driving
featured: false

hugoblox:
  ids:
    doi: "10.1109/IV48863.2021.9575937"

links:
- type: custom
  label: Conference
  url: https://2021.ieee-iv.org/
- type: custom
  label: Proceedings
  url: "https://doi.org/10.1109/IV48863.2021"
- type: pdf
  url: "https://www.researchgate.net/publication/351880952_Trajectory-Based_Failure_Prediction_for_Autonomous_Driving"
- type: project
  url: https://www.researchgate.net/project/Failure-Prediction-in-Autonomous-Driving
- type: slides
  url: https://drive.google.com/file/d/1e2BYFGVyFNvmLoEYIZ0ozHIBmuKF_qkj/view
- type: video
  url: https://youtu.be/OP_3ErP5CU8

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**IEEE**](https://doi.org/10.1109/IV48863.2021.9575937)'
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
