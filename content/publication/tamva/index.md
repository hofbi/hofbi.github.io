---
title: "Traffic-Aware Multi-View Video Stream Adaptation for Teleoperated Driving"
authors:
- admin
- Christopher Kuhn
- Mariem Khlifi
- Goran Petrovic
- Eckehard Steinbach
date: "2022-06-19T00:00:00Z"
doi: "10.1109/VTC2022-Spring54318.2022.9860513"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-03-04T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2022 IEEE 95th Vehicular Technology Conference*
publication_short: In *VTC2022-Spring*

abstract: "Remote control of an autonomous vehicle by a human operator requires low delay video transmission to resolve complex situations and ensure safety. The remote operator perceives the current traffic scenario via video streams from multiple cameras. To provide the operator with the best possible scene understanding while matching the available network resources, the video streams need to be automatically adapted. In this paper, we propose a traffic-aware multi-view video stream adaptation scheme. We estimate the importance of each camera view based on the vehicle's real-time movement in traffic. The resulting prioritization together with the total available transmission rate determines a specific bit-budget for each camera view. We optimize the video quality of each individual video stream for the given bit-budget using a quality-of-experience-driven multi-dimensional adaptation scheme. Additionally, we apply a region-of-interest mask to the rear-facing camera views. The mask removes less important areas from the image which reduces the required bitrate. All modules are implemented to extend the existing TELECARLA framework. We evaluate the proposed traffic-aware adaptation scheme in a user study. We observe a high correlation between the proposed view prioritization module and the subjective ratings obtained in the user study. The region-of-interest masking achieves Bjontegaard Delta Rate savings of at least 19.8% compared to streaming the full camera view. The overall system improves the VMAF score by 1.86 per camera when considering the importance of the individual camera views as rated by the users. This demonstrates the potential of an individual adaptation for each camera view optimized for the current traffic situation."

# Summary. An optional shortened abstract.
summary: ""

tags:
- Teleoperated Driving
- Adaptive Video Streaming
- C++
- ROS
- CARLA
featured: false

links:
- name: Conference
  url: https://events.vtsociety.org/vtc2022-spring/
- name: Proceedings
  url: https://doi.org/10.1109/VTC2022-Spring54318.2022
url_pdf: "https://www.researchgate.net/publication/360040983_Traffic-Aware_Multi-View_Video_Stream_Adaptation_for_Teleoperated_Driving"
url_code: 'https://github.com/hofbi/tamva'
url_dataset: ''
url_poster: ''
url_project: 'https://www.researchgate.net/project/Adaptive-Streaming-of-Sensor-Information-for-Teleoperator-Situation-Awareness'
url_slides: 'https://drive.google.com/file/d/1lLqODFjt3deqXt14yjitQa2Pz-oB2Cf9/view'
url_source: ''
url_video: 'https://youtu.be/EKUehisnO6c'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**IEEE**](https://doi.org/10.1109/VTC2022-Spring54318.2022.9860513)'
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
