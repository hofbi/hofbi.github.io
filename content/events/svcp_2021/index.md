---
title: Adaptive Multi-View Live Video Streaming for Teledriving Using a Single Hardware Encoder
event: 6th ITG/VDE Graduate Summer School on Video Compression and Processing
event_url: https://www.3it-berlin.de/events/summer-school-on-video-coding-and-processing-svcp2020/

location: Fraunhofer Heinrich Hertz Institute
address:
  street: Salzufer 6
  city: Berlin
  region: BE
  postcode: '10587'
  country: Germany

summary: "Talk at the 6th ITG/VDE Graduate Summer School on Video Compression and Processing about adaptive multi-view live video streaming for teledriving using a single hardware encoder"
abstract: "Teleoperated driving (TOD) is a possible solution to cope with failures of autonomous vehicles. In TOD, the human operator perceives the traffic situation via video streams of multiple cameras from a remote location. Adaptation mechanisms are needed in order to match the available transmission resources and provide the operator with the best possible situation awareness. This includes the adjustment of individual camera video streams according to the current traffic situation. The limited video encoding hardware in vehicles requires the combination of individual camera frames into a larger superframe video. While this enables the encoding of multiple camera views with a single encoder, it does not allow for rate/quality adaptation of the individual views. To this end, we propose a novel concept that uses preprocessing filters to enable individual rate/quality adaptations in the superframe video. The proposed preprocessing filters allow for the usage of existing multidimensional adaptation models in the same way as for individual video streams using multiple encoders. Our experiments confirm that the proposed concept is able to control the spatial, temporal and quality resolution of individual segments in the superframe video. Additionally, we demonstrate the usability of the proposed method by applying it in a multi-view teledriving scenario. We compare our approach to individually encoded video streams and a multiplexing solution without preprocessing. The results show that the proposed approach produces bitrates for the individual video streams which are comparable to the bitrates achieved with separate encoders. In contrast, the multiplexing approach without preprocessing either exceeds the total bitrate by 60% for a similar bitrate on the most important views or remains 33% under the bitrate for the important views while matching the total bitrate."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2021-07-26T17:00:00Z"
date_end: "2021-07-26T17:30:00Z"
all_day: false

publishDate: "2021-07-25T19:00:00Z"

authors:
- me
tags:
- "Adaptive Video Streaming"
- "Teleoperated Driving"

# Is this a featured talk? (true/false)
featured: true

image:
  caption: ''
  focal_point: Right

links:
- type: custom
  label: Event
  url: https://www.3it-berlin.de/events/summer-school-on-video-coding-and-processing-svcp2020/
- type: code
  url: "https://github.com/hofbi/amvs-se"
- type: slides
  url: "https://drive.google.com/file/d/18vbIqz3sVicwvaNAwDDY5GgjxCKHNPP6/view"
---
