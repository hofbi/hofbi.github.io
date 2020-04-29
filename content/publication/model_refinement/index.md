---
title: "Situation-Aware Model Refinement for Semantic Image Segmentation"
authors:
- Lukas Habermayr
- admin
- Joao-Vitor Zacchi
- Christopher Kuhn
date: "2021-09-19T00:00:00Z"
doi: "10.1109/ITSC48978.2021.9564549"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-05-08T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *24th IEEE International Conference on Intelligent Transportation*
publication_short: In *ITSC2021*

abstract: "The quality of semantic image segmentation models can be affected by external factors such as weather or daytime. Those factors can lead to safety-critical mistakes. In this work, we propose a systematic approach to detect and alleviate such weaknesses of semantic segmentation models. We systematically evaluate a semantic segmentation model under different external factors and analyze which factors have the largest impact on the performance. Then, we collect new training data under the most harmful external factors and fine-tune the model. We use the CARLA simulator to obtain driving data under various environment settings. We deploy a state-of-the-art semantic segmentation model in two distinct driving environments. Then, we use the proposed process to detect which external factors affect model performance the most. We collect new training data under those factors and fine-tune the model. The proposed approach outperforms collecting the same amount of random additional data by up to 10.6%. Our results show the benefit of using an iterative refinement approach as opposed to merely collecting larger data sets. Finally, we use the knowledge about which factors affect performance the most to train a simple decision tree classifier to predict the model's performance given the current external factors. Problematic environments can be detected at an average accuracy of 87.5%."

# Summary. An optional shortened abstract.
summary: ""

tags:
- Model Refinement
- Semantic Segmentation
featured: false

links:
- name: Conference
  url: https://2021.ieee-itsc.org/
- name: Proceedings
  url: "https://doi.org/10.1109/ITSC48978.2021"
url_pdf: "https://www.researchgate.net/publication/352737369_Situation-Aware_Model_Refinement_for_Semantic_Image_Segmentation"
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://www.researchgate.net/project/Failure-Prediction-in-Autonomous-Driving'
url_slides: 'https://drive.google.com/file/d/1fYAmiqBhifhiDc4CSWu3tI_amw-5KlKb/view'
url_source: ''
url_video: 'https://youtu.be/fa4lCBOsh-k'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**IEEE**](https://doi.org/10.1109/ITSC48978.2021.9564549)'
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
