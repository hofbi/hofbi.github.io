---
title: "Adaptive Multi-View Live Video Streaming for Teledriving Using a Single Hardware Encoder"
authors:
- admin
- Christopher Kuhn
- Goran Petrovic
- Eckehard Steinbach
date: "2020-12-02T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-10-12T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *22nd IEEE International Symposium on Multimedia*
publication_short: In *ISM2020*

abstract: "Teleoperated driving (TOD) is a possible solution to cope with failures of autonomous vehicles. In TOD, the human operator perceives the traffic situation via video streams of multiple cameras from a remote location. Adaptation mechanisms are needed in order to match the available transmission resources and provide the operator with the best possible situation awareness. This includes the adjustment of individual camera video streams according to the current traffic situation. The limited video encoding hardware in vehicles requires the combination of individual camera frames into a larger superframe video. While this enables the encoding of multiple camera views with a single encoder, it does not allow for rate/quality adaptation of the individual views. To this end, we propose a novel concept that uses preprocessing filters to enable individual rate/quality adaptations in the superframe video. The proposed preprocessing filters allow for the usage of existing multidimensional adaptation models in the same way as for individual video streams using multiple encoders. Our experiments confirm that the proposed concept is able to control the spatial, temporal and quality resolution of individual segments in the superframe video. Additionally, we demonstrate the usability of the proposed method by applying it in a multi-view teledriving scenario. We compare our approach to individually encoded video streams and a multiplexing solution without preprocessing. The results show that the proposed approach produces bitrates for the individual video streams which are comparable to the bitrates achieved with separate encoders. While achieving a similar bitrate for the most important views, our approach requires a total bitrate that is 40% smaller compared to the multiplexing approach without preprocessing."

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
    doi: "10.1109/ISM.2020.00008"

links:
- type: custom
  label: Conference
  url: https://www.ieee-ism.org/
- type: custom
  label: Proceedings
  url: https://doi.org/10.1109/ISM50513.2020
- type: pdf
  url: "https://www.researchgate.net/publication/345241096_Adaptive_Multi-View_Live_Video_Streaming_for_Teledriving_Using_a_Single_Hardware_Encoder"
- type: code
  url: 'https://github.com/hofbi/amvs-se'
- type: project
  url: 'https://www.researchgate.net/project/Adaptive-Streaming-of-Sensor-Information-for-Teleoperator-Situation-Awareness'
- type: slides
  url: 'https://drive.google.com/file/d/1ioTdB6LsWJQV8fANITRrRFWAtwKFNvnm/view'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**IEEE**](https://doi.org/10.1109/ISM.2020.00008)'
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
