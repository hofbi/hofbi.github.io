---
title: "Introspective Failure Prediction for Autonomous Driving Using Late Fusion of State and Camera Information"
authors:
- Christopher Kuhn
- admin
- Goran Petrovic
- Eckehard Steinbach
date: "2020-12-20T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-12-20T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Intelligent Transportation Systems*
publication_short: In *TITS*

abstract: "We present an introspective failure prediction approach for autonomous vehicles. In autonomous driving, complex or unknown scenarios can cause a disengagement of the self-driving system. Disengagements can be triggered either by automatic safety measures or by human intervention. We propose to use recorded disengagement sequences from test drives as training data to learn to predict future failures. The system then learns introspectively from its own previous mistakes. In order to predict failures as early as possible, we propose a machine learning approach where sequences of sensor data are classified as either failure or success. The car itself is treated as a black box. Our method combines two sensor modalities that contain different types of information. An image-based model learns to detect generally challenging situations such as crowded intersections accurately multiple seconds in advance. A state data based model allows to detect fast changes immediately before a failure, such as sudden braking or swerving. The outcome of the individual models is fused by averaging the individual failure probabilities. We evaluate our approach on a data set provided by the BMW Group containing 14 hours of autonomous driving. The proposed late fusion approach allows for predicting failures at an accuracy of more than 85% seven seconds in advance, at a false positive rate of 20%. The proposed method outperforms state-of-the-art failure prediction by more than 15% while being a flexible framework that allows for straightforward addition of further sensor modalities."

# Summary. An optional shortened abstract.
summary: ""

tags:
- Failure Prediction
- Autonomous Driving
featured: false

hugoblox:
  ids:
    doi: "10.1109/TITS.2020.3044813"

links:
- type: custom
  label: Journal
  url: https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=6979
- type: custom
  label: Press Release
  url: https://www.tum.de/nc/en/about-tum/news/press-releases/details/36509/
- type: pdf
  url: https://www.researchgate.net/publication/348052655_Introspective_Failure_Prediction_for_Autonomous_Driving_Using_Late_Fusion_of_State_and_Camera_Information
- type: project
  url: https://www.researchgate.net/project/Failure-Prediction-in-Autonomous-Driving

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**IEEE**](https://doi.org/10.1109/TITS.2020.3044813)'
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
