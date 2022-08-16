---
title: "SingleChannelNet: A model for automatic sleep stage classification with raw single-channel EEG"
collection: publications
permalink: /publication/SCNet
excerpt: 
date: 2022-05-01
venue: 'Biomedical Signal Processing and Control (BSPC) '
paperurl: 'https://www.sciencedirect.com/science/article/pii/S1746809422001148'
citation: 
---

[Paper](https://www.sciencedirect.com/science/article/pii/S1746809422001148)
[Code](https://github.com/zhangjinyangnwpu/LDCR)

Abstract:
In diagnosing sleep disorders, sleep stage classification is a very essential yet time-consuming process. Various existing state-of-the-art approaches rely on hand-crafted features and multi-modality polysomnography (PSG) data, where prior knowledge is compulsory and high computation cost can be expected. Besides, it is a big challenge to handle the task with raw single-channel electroencephalogram (EEG). To overcome these shortcomings, this paper proposes an end-to-end framework with a deep neural network, namely SingleChannelNet, for automatic sleep stage classification based on raw single-channel EEG. The proposed model utilizes a 90s epoch as the textual input and employs two multi-convolution (MC) blocks and several max-average pooling (M-Apooling) layers to learn different scales of feature representations. To demonstrate the efficiency of the proposed model, we evaluate our model using different raw single-channel EEGs (C4/A1 and Fpz-Cz) on two public PSG datasets (Cleveland children’s sleep and health study: CCSHS and Sleep-EDF database expanded: Sleep-EDF). Experimental results show that the proposed architecture can achieve better overall accuracy and Cohen’s kappa (CCSHS: 90.2%–86.5%, Sleep-EDF: 86.1%–80.5%) compared with state-of-the-art approaches. Additionally, the proposed model can learn features automatically for sleep stage classification using different single-channel EEGs with distinct sampling rates and without using any hand-engineered features.
