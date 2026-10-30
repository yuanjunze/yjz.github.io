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

abstract: "Estimating a person’s readiness to engage is a critical prerequisite for achieving natural interactions with machines. In this work, we explore a skeleton-based approach for estimating interaction readiness from human motion. A two-stream spatio-temporal graph convolutional network is applied as backbone. We propose two design changes to the backbone: Local Dense Connection (LDC), which enhances the flow of multi-scale features, and Cross-Stream Attention (CSA) module, allowing it to effectively relate joint and bone features. Rather than classifying actions directly, a probabilistic aggregation strategy is introduced to generate a scalar measure of interaction readiness, which helps the model generalize better to real-world scenes. Experiment on the processed NTU-RGB+D 120 dataset demonstrates the proposed method achieves 82.52% top-1 accuracy, outperforming backbone model. Moreover, experiment on real-world data achieves ROC-AUC = 0.9687 in realistic conditions, indicating the robustness and generalization ability of the proposed method with lightweight parameters (8.30 M). While relatively lightweight, the method offers a practical solution for scenarios that require fast, interpretable estimation such as human-robot interaction settings."


# links:
# - name: ""
#   url: ""
featured: true

url_pdf: ''
url_code: 'https://github.com/yuanjunze/Skeleton-based-interaction-readiness-estimation'
url_source: 'https://www.sciencedirect.com/science/article/pii/S0167865526000681'

image:
  caption: 'Overview'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
