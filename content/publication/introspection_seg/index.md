---
title: "Introspective Failure Prediction for Semantic Image Segmentation"
authors:
- Christopher Kuhn
- admin
- Sungkyu Lee
- Goran Petrovic
- Eckehard Steinbach
date: "2020-09-20T00:00:00Z"
doi: "10.1109/ITSC45102.2020.9294308"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-05-08T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *23rd IEEE International Conference on Intelligent Transportation Systems*
publication_short: In *ITSC2020*

abstract: "Semantic segmentation of images enables pixel-wise scene understanding which in turn is a critical component for tasks such as autonomous driving. While recent implementations of semantic image segmentation have achieved remarkable accuracy, misclassifications remain inevitable. For safety-critical tasks such as free-space computing, it is desirable to know when and where the segmentation will fail. We propose using the concept of introspection to predict the failures of a given semantic segmentation model. A separate introspective model is trained to predict the errors of a given model. This is accomplished by training the given model with the errors made on a set of previous inputs. By using the same architecture for the introspective model as for the semantic segmentation, the proposed model learns to predict pixel-wise failure probabilities. This allows to predict both when and where the semantic segmentation will fail. Sharing the feature encoder with the inspected model reduces training and inference time while improving performance. We evaluate our approach on the large-scale A2D2 driving data set. In a precision-recall analysis, the proposed method outperforms two state-of-the-art uncertainty estimation methods by 3.2% and 6.7% while requiring significantly less resources during inference. Additionally, combining introspection with a state-of-the-art method further increases the performance by up to 3.7%."

# Summary. An optional shortened abstract.
summary: ""

tags:
- Teleoperated Driving
- Failure Prediction
featured: false

links:
- name: Conference
  url: https://www.ieee-itsc2020.org/
- name: Proceedings
  url: https://doi.org/10.1109/ITSC45102.2020
url_pdf: "https://www.researchgate.net/publication/342171446_Introspective_Failure_Prediction_for_Semantic_Image_Segmentation"
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://www.researchgate.net/project/Failure-Prediction-in-Autonomous-Driving'
url_slides: 'https://drive.google.com/file/d/1sl6q-B8CG-hJSbzPrDTo7CDF3dDrCHjW/view'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
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
