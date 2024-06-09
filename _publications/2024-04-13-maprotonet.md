---
title: "MAProtoNet: A Multi-scale Attentive Interpretable Prototypical Part Network for 3D Magnetic Resonance Imaging Brain Tumor Classification"
collection: publications
permalink: /publication/maprotonet
excerpt: 'This work proposes a novel interpretable model named MAProtoNet for brain tumor classification using brain MRI data.'
date: 2024-04-13
venue: 'arXiv'
slidesurl: ''
paperurl: 'https://export.arxiv.org/abs/2404.08917'
codeurl: 'https://github.com/TUAT-Novice/maprotonet'
citation: 'Binghua Li, Jie Mao, Zhe Sun, Chao Li, Qibin Zhao, Toshihisa Tanaka. MAProtoNet: A Multi-scale Attentive
Interpretable Prototypical Part Network for 3D Magnetic Resonance Imaging Brain Tumor Classification. arXiv
preprint arXiv:2404.08917, 2024.'
pubtype: 'journal'
---

Automated diagnosis with artificial intelligence has emerged as a promising area in the realm of medical imaging, while the interpretability of the introduced deep neural networks still remains an urgent concern. Although contemporary works, such as XProtoNet and MProtoNet, has sought to design interpretable prediction models for the issue, the localization precision of their resulting attribution maps can be further improved. To this end, we propose a Multi-scale Attentive Prototypical part Network, termed MAProtoNet, to provide more precise maps for attribution. Specifically, we introduce a concise multi-scale module to merge attentive features from quadruplet attention layers, and produces attribution maps. The proposed quadruplet attention layers can enhance the existing online class activation mapping loss via capturing interactions between the spatial and channel dimension, while the multi-scale module then fuses both fine-grained and coarse-grained information for precise maps generation. We also apply a novel multi-scale mapping loss for supervision on the proposed multi-scale module. Compared to existing interpretable prototypical part networks in medical imaging, MAProtoNet can achieve state-of-the-art performance in localization on brain tumor segmentation (BraTS) datasets, resulting in approximately 4% overall improvement on activation precision score (with a best score of 85.8%), without using additional annotated labels of segmentation. Our code will be released in [https://github.com/TUAT-Novice/maprotonet](https://github.com/TUAT-Novice/maprotonet)
