---
title: "A Deep Learning Model for Automatic Sleep Scoring using Multimodality Time Series"
collection: publications
permalink: /publication/EUSIPCO
excerpt: 
date: 2021-01-18
venue: '28th European Signal Processing Conference (EUSIPCO)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9287518'
citation: 
---

[Paper](https://ieeexplore.ieee.org/abstract/document/9287518)

Abstract:
Sleep scoring is a fundamental but time-consuming process in any sleep laboratory. Automatic sleep scoring is crucial and urgent to help address the increasing unmet need for sleep research. Therefore, this paper aims to develop an end-to-end deep learning architecture using raw polysomnographic recordings to automate sleep scoring. The proposed model adopts two-dimensional convolutional neural networks (2D-CNN) to automatically learn features from multi-modality signals, together with a "squeeze and excitation" block for recalibrating channel-wise feature responses. The learnt representations are finally fed to a softmax classifier to generate predictions for each sleep stage. The model performance is evaluated on two public sleep datasets (SHHS and Sleep-EDF) with different available channels. The results have shown that our model achieves an overall accuracy of 85.2% on the SHHS dataset and an accuracy of 85% on the Sleep-EDF dataset. We have also demonstrated that the proposed architecture not only is able to handle various numbers of input channels and several signal modalities from different datasets but also exhibits short runtimes and low computational cost.
