---
title: "Skeleton-Based Interaction Readiness Estimation"
summary: "Estimating human interaction readiness from skeleton motion using a two-stream spatio-temporal graph convolutional network."
date: "2026-05-01"

image:
  caption: "Overview"
  focal_point: Smart
  path: content\project\skeleton-interaction-readiness\featured.png

tags:
  - Human-Robot Interaction
  - Deep Learning
  - Skeleton-Based Perception
  - ST-GCN

url_pdf: "https://doi.org/10.1016/j.patrec.2026.02.021"
---

## Overview

This project investigates skeleton-based estimation of human interaction readiness for proactive human-robot interaction. The goal is to estimate how ready a person is to initiate interaction based on recent body movements.

## Method

The proposed Skeleton-Based Interaction Potential Detection (SIPD) framework employs a two-stream spatio-temporal graph convolutional network to extract joint and bone motion features.

The framework integrates three components:

- **Local Dense Connection (LDC):** Enhances multi-scale feature propagation.
- **Cross-Stream Attention (CSA):** Models relationships between joint and bone features.
- **Probability Aggregation (PA):** Converts action classification probabilities into a continuous interaction readiness score.

## Results

Evaluated on the processed NTU RGB+D 120 dataset and real-world recordings.

- 82.52% Top-1 action recognition accuracy.
- 83% interaction readiness classification accuracy in real-world experiments.
- 8.30 million model parameters.
- 15.71 ms inference latency per 75-frame clip on NVIDIA Jetson AGX Orin.

## Publication

Skeleton-based estimation of interaction readiness via spatio-temporal graph convolution.

*Pattern Recognition Letters*, 2026.
