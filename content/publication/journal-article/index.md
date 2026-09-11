---
title: "Skeleton-based estimation of interaction readiness via spatio-temporal graph convolution"
authors:
- Yuan, Junze
- Mohammed, Wael M
- Perez, Manuel Ferre
- Lastra, Jose L Martinez
date: "2026-05"
doi: "10.1016/j.patrec.2026.02.021"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-05"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Pattern Recognition Letters"
publication_short: ""

abstract: Estimating a person’s readiness to engage is a critical prerequisite for achieving natural interactions with machines. In this work, we explore a skeleton-based approach for estimating interaction readiness from human motion. A two-stream spatio-temporal graph convolutional network is applied as backbone. We propose two design changes to the backbone: Local Dense Connection (LDC), which enhances the flow of multi-scale features, and Cross-Stream Attention (CSA) module, allowing it to effectively relate joint and bone features. Rather than classifying actions directly, a probabilistic aggregation strategy is introduced to generate a scalar measure of interaction readiness, which helps the model generalize better to real-world scenes. Experiment on the processed NTU-RGB+D 120 dataset demonstrates the proposed method achieves 82.52% top-1 accuracy, outperforming backbone model. Moreover, experiment on real-world data achieves ROC-AUC = 0.9687 in realistic conditions, indicating the robustness and generalization ability of the proposed method with lightweight parameters (8.30 M). While relatively lightweight, the method offers a practical solution for scenarios that require fast, interpretable estimation such as human-robot interaction settings.


# links:
# - name: ""
#   url: ""
url_pdf: [http://arxiv.org/pdf/1512.04133v1](https://www.sciencedirect.com/science/article/pii/S0167865526000681)
url_code: '[https://github.com/HugoBlox/hugo-blox-builder](https://github.com/yuanjunze/Skeleton-based-interaction-readiness-estimation)'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
