---
title: "Preprocessor Rate Control for Adaptive Multi-View Live Video Streaming Using a Single Encoder"
authors:
- admin
- Christopher Kuhn
- Goran Petrovic
- Eckehard Steinbach
date: "2022-01-12T00:00:00Z"
doi: "10.1109/TCSVT.2022.3142403"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-12T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Circuits and Systems for Video Technology*
publication_short: In *CSVT*

abstract: "Currently, an increasing number of technical systems are equipped with multiple cameras. Limited by cost and size, they are often restricted to a single hardware encoder. The combination of all views into a single superframe allows for streaming all camera views at the same time, but it prevents individual rate/quality adaptations on those camera views. We propose a preprocessing filter concept that allows for individual rate/quality adaptation while using a single encoder. Additionally, we create a preprocessor model that estimates the required preprocessing filter parameters from the specified encoding parameters. This means our approach can be used with any existing multi-view adaptation scheme designed for controlling multiple encoders. We design both an analytical and a Machine Learning-based bitrate model. Because both models perform equally well, we suggest using either one as the core part of our preprocessor model. Both models are specifically designed for estimating the influence of the quantization parameter, frame rate, frame size, group of pictures length, and a Gaussian low-pass filter on the video bitrate. Furthermore, the rate models outperform state-of-the-art bitrate models by at least 22% regarding the overall root mean square error. Our bitrate models are the first of their kind to consider the influence of a Gaussian low-pass filter. We evaluate the preprocessing approach by streaming six camera views in a teledriving scenario with a single encoder and compare it to using six individual encoders. The experimental results demonstrate that the preprocessing approach achieves bitrates similar to the individual encoders for all views. While achieving a comparable rate and quality for the most important views, our approach requires a total bitrate that is 50% smaller than when using a single encoder approach without preprocessing. "

# Summary. An optional shortened abstract.
summary: ""

tags:
- Teleoperated Driving
- Adaptive Video Streaming
- C++
- ROS
featured: true

links:
- name: Journal
  url: https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=76
url_pdf: "https://www.researchgate.net/publication/357826860_Preprocessor_Rate_Control_for_Adaptive_Multi-View_Live_Video_Streaming_Using_a_Single_Encoder"
url_code: 'https://github.com/hofbi/amvs-se'
url_dataset: ''
url_poster: ''
url_project: 'https://www.researchgate.net/project/Adaptive-Streaming-of-Sensor-Information-for-Teleoperator-Situation-Awareness'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**IEEE**](https://doi.org/10.1109/TCSVT.2022.3142403)'
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
