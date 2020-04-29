---
title: "Measuring the Influence of Image Preprocessing on the Rate-Distortion Performance of Video Encoding"
authors:
- me
- Christopher Kuhn
- Goran Petrovic
- Eckehard Steinbach
date: "2022-12-05T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-10-27T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *24nd IEEE International Symposium on Multimedia*
publication_short: In *ISM2022*

abstract: "In image and video coding, preprocessing of the images allows to increase the perceptual quality or to control the bitrate. In this paper, we conduct an extensive analysis of the rate-distortion (RD) performance achieved by using different preprocessing steps before encoding the video. We propose a novel evaluation method called the Mean Saving-Cost Ratio (MSCR) to compare the RD performance for different preprocessing algorithms. We define MSCR as the logarithmic mean ratio of maximum bitrate savings over maximum quality cost for all parameters of a preprocessing algorithm. Further, we calculate the Bjontegaard Delta Rate for every quantization parameter (QP) between two RD curves at the respective QP. The resulting Bjontegaard Delta curves allow for comparing two preprocessing algorithms over a range of QPs. In our experiments, we use the proposed MSCR to compare different preprocessing algorithms such as a Gaussian low-pass filter, a median filter, and a JPEG compressor. Overall, the Gaussian low-pass filter shows the best RD performance according to MSCR."

# Summary. An optional shortened abstract.
summary: ""

tags:
- Teleoperated Driving
- Adaptive Video Streaming
- C++
- ROS
featured: false

hugoblox:
  ids:
    doi: "10.1109/ISM55400.2022.00030"

links:
- type: custom
  label: Conference
  url: https://www.ieee-ism.org/
- type: custom
  label: Proceedings
  url: https://doi.org/10.1109/ISM55400.2022
- type: custom
  label: Extended Version
  url: https://www.researchgate.net/publication/364997199_Measuring_the_Influence_of_Image_Preprocessing_on_the_Rate-Distortion_Performance_of_Video_Encoding
- type: pdf
  url: https://www.researchgate.net/publication/364997113_Measuring_the_Influence_of_Image_Preprocessing_on_the_Rate-Distortion_Performance_of_Video_Encoding
- type: code
  url: 'https://github.com/hofbi/amvs-se'
- type: project
  url: 'https://www.researchgate.net/project/Adaptive-Streaming-of-Sensor-Information-for-Teleoperator-Situation-Awareness'
- type: slides
  url: 'https://drive.google.com/file/d/1P5mfyUEvqc-z3AgUpw-BrS3jvHAImplV/view'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**IEEE**](https://doi.org/10.1109/ISM55400.2022.00030)'
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
