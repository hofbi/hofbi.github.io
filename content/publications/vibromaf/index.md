---
title: "Automated Quality Assessment for Compressed Vibrotactile Signals Using Multi-Method Assessment Fusion"
authors:
- Andreas Noll
- admin
- Evelyn Muschter
- Shu-Chen Li
- Eckehard Steinbach
date: "2022-03-21T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-03T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Haptics Symposium 2022*
publication_short: In *HAPTICS2022*

abstract: "Design and optimization of vibrotactile codecs require precise measurements of the compressed signals’ perceptual quality. In this paper, we present two computational approaches for estimating vibrotactile signal quality. First, we propose a novel full-reference vibrotactile quality metric called Spectral Perceptual Quality Index (SPQI), which computes a similarity score based on a computed perceptually weighted error measure. Second, we use the concept of Multi-Method Assessment Fusion (MAF) to predict the subjective quality. MAF uses a Support Vector Machine regressor to fuse multiple elementary metrics into a final quality score, which preserves the strengths of the individual metrics. We evaluate both proposed quality assessment methods on an extended subjective dataset, which we introduce as part of this work. For two of three tested vibrotactile codecs, the MSE between subjective ratings and the SPQI is reduced by 64% and 92%, respectively compared to the state of the art. With our MAF approach, we obtain the only currently available metric that accurately predicts real human user experiments for all three tested codecs. The MAF estimations reduce the average MSE to the subjective ratings over all three tested codecs by 59% compared to the best performing elementary metric."

# Summary. An optional shortened abstract.
summary: ""

tags:
- Haptics
- Python
featured: false

hugoblox:
  ids:
    doi: "10.1109/HAPTICS52432.2022.9765599"

links:
- type: custom
  label: Conference
  url: https://2022.hapticssymposium.org/
- type: custom
  label: Proceedings
  url: https://doi.org/10.1109/HAPTICS52432.2022
- type: pdf
  url: "https://www.researchgate.net/publication/357556145_Automated_Quality_Assessment_for_Compressed_Vibrotactile_Signals_Using_Multi-Method_Assessment_Fusion"
- type: code
  url: 'https://github.com/hofbi/vibromaf'
- type: video
  url: 'https://youtu.be/2Az1ZunbkHY'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**IEEE**](https://doi.org/10.1109/HAPTICS52432.2022.9765599)'
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
