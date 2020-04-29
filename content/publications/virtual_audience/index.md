---
title: "Enabling Acoustic Audience Feedback in Large Virtual Events"
authors:
- Tamay Aykut
- admin
- Christopher Kuhn
- Eckehard Steinbach
- Bernd Girod
date: "2023-10-27T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-10-27T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: In *arXiv Multimedia (cs.MM)*
publication_short: In *arXiv*

abstract: "The COVID-19 pandemic shifted many events in our daily lives into the virtual domain. While virtual conference systems provide an alternative to physical meetings, larger events require a muted audience to avoid an accumulation of background noise and distorted audio. However, performing artists strongly rely on the feedback of their audience. We propose a concept for a virtual audience framework which supports all participants with the ambience of a real audience. Audience feedback is collected locally, allowing users to express enthusiasm or discontent by selecting means such as clapping, whistling, booing, and laughter. This feedback is sent as abstract information to a virtual audience server. We broadcast the combined virtual audience feedback information to all participants, which can be synthesized as a single acoustic feedback by the client. The synthesis can be done by turning the collective audience feedback into a prompt that is fed to state-of-the-art models such as AudioGen. This way, each user hears a single acoustic feedback sound of the entire virtual event, without requiring to unmute or risk hearing distorted, unsynchronized feedback."

# Summary. An optional shortened abstract.
summary: ""

tags:
- Audio
- Sound Generation
featured: false

links:
- type: pdf
  url: 'https://arxiv.org/pdf/2310.18099.pdf'
- type: code
  url: 'https://github.com/Virtual-Audience-Synthesis'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: '' #'Image credit: [**TBD**](https://doi.org/tbd)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
