---
title: "Multi-View Region of Interest Prediction for Autonomous Driving Using Semi-Supervised Labeling"
authors:
- me
- Christopher Kuhn
- Jiaming Meng
- Goran Petrovic
- Eckehard Steinbach
date: "2020-09-20T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-05-08T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *23rd IEEE International Conference on Intelligent Transportation Systems*
publication_short: In *ITSC2020*

abstract: "Visual environment perception is one of the key elements for autonomous and manual driving. Modern fully automated vehicles are equipped with a range of different sensors and capture the surroundings with multiple cameras. The ability to predict human driver's attention is the basis for various autonomous driving functions. State-of-the-art attention prediction approaches use only a single front facing camera and rely on automatically generated training data. In this paper, we present a manually labeled multi-view region of interest dataset. We use our dataset to finetune a state-of-the-art region of interest prediction model for multiple camera views. Additionally, we show that using two separate models focusing on either front or rear view data improves the region of interest prediction. We further propose a semi-supervised annotation framework which uses the best performing finetuned models for generating pseudo labels to improve the efficiency of the labeling process. Our results show that existing region of interest prediction performs well on front view data, but finetuning improves the performance especially for rear view data. Our current dataset consists of about 16000 images and we plan to further increase the size of the dataset. The dataset and the source code of the proposed semi-supervised annotation framework will be made available on GitHub and can be used to generate custom region of interest data."

# Summary. An optional shortened abstract.
summary: ""

tags:
- ROI Prediction
- Python
- CARLA
featured: false

hugoblox:
  ids:
    doi: "10.1109/ITSC45102.2020.9294387"

links:
- type: custom
  label: Conference
  url: https://www.ieee-itsc2020.org/
- type: custom
  label: Proceedings
  url: https://doi.org/10.1109/ITSC45102.2020
- type: pdf
  url: "https://www.researchgate.net/publication/342171521_Multi-View_Region_of_Interest_Prediction_for_Autonomous_Driving_Using_Semi-Supervised_Labeling"
- type: code
  url: 'https://github.com/hofbi/mv-roi'
- type: dataset
  url: 'https://mediatum.ub.tum.de/1548761'
- type: project
  url: 'https://www.researchgate.net/project/Adaptive-Streaming-of-Sensor-Information-for-Teleoperator-Situation-Awareness'
- type: slides
  url: 'https://drive.google.com/file/d/1RhcA6dBEbDUEGry0pHsCpL5R0dg92oN9/view'
- type: video
  url: 'https://youtu.be/RzxFkpKRiMw'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**IEEE**](https://doi.org/10.1109/ITSC45102.2020.9294387)'
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
