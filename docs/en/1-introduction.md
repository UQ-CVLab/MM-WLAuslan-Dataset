---
layout: page
title: MM-WLAuslan
permalink: /docs/en/introduction
key: docs-introduction
article_header:
  type: cover
  theme: dark
  image:
    src: /docs/assets/images/mm_wlauslan_fs.png
---


<div>{%- include extensions/youtube.html id='x4ckW_cj8q8' -%}</div>


**Isolated Sign Language Recognition (ISLR)** focuses on identifying individual sign language glosses.
Considering the diversity of sign languages across geographical regions, developing region-specific ISLR datasets is crucial for supporting communication and research.
Auslan, as a sign language specific to Australia, still lacks a dedicated large-scale word-level dataset for the ISLR task.
To fill this gap, we curate **<u>the first</u>** large-scale Multi-view Multi-modal Word-Level Australian Sign Language recognition dataset, dubbed MM-WLAuslan.
Compared to other publicly available datasets, MM-WLAuslan exhibits three significant advantages: (1) **<u>the largest amount</u>** of data, (2) **<u>the most extensive</u>** vocabulary, and (3) **<u>the most diverse</u>** of multi-modal camera views.
Specifically, we record **282K+** sign videos covering **3,215** commonly used Auslan glosses presented by **73** signers in a studio environment.
Moreover, our filming system includes two different types of cameras, i.e., three Kinect-V2 cameras and a RealSense camera.
We position cameras hemispherically around the front half of the model and simultaneously record videos using all four cameras.
Furthermore, we benchmark results with state-of-the-art methods for various multi-modal ISLR settings on MM-WLAuslan, including multi-view, cross-camera, and cross-view.
Experiment results indicate that MM-WLAuslan is a challenging ISLR dataset, and we hope this dataset will contribute to the development of Auslan and the advancement of sign languages worldwide.
