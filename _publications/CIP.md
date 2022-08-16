---
title: "Alleviating Class Imbalance Problem in Automatic Sleep Stage Classification"
collection: publications
permalink: /publication/CIP
excerpt: 
date: 2022-07-18
venue: 'IEEE Transactions on Instrumentation and Measurement (TIM) '
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9832012'
citation: 
---

[Paper](https://ieeexplore.ieee.org/abstract/document/9832012)
[Code](https://github.com/zhangjinyangnwpu/LDCR)

Abstract:
For real-world automatic sleep-stage classification tasks, various existing deep learning-based models are biased toward the majority with a high proportion. Because of the unique sleep structure, most of the current polysomnography (PSG) datasets suffer an inherent class imbalance problem (CIP), in which the number of each sleep stage is severely unequal. In this study, we first define the class imbalance factor (CIF) to describe the level of CIP quantitatively. Afterward, we propose two balancing methods to alleviate this problem from the dataset quantity and the relationship between the class distribution and the applied model, respectively. The first one is to employ the data augmentation (DA) with the generative adversarial network (GAN) model and different intensities of Gaussian white noise (GWN) to balance samples, thereinto, GWN addition is specifically tailored to deep learning-based models, which can work on raw electroencephalogram (EEG) data while preserving their properties. In addition, we try to balance the relationship between the imbalanced class and biased network model to achieve a balanced state with the help of class distribution and neuroscience principles. We further propose an effective deep convolutional neural network (CNN) model utilizing bidirectional long short-term memory (Bi-LSTM) with single-channel EEG as the baseline. It is used for evaluating the efficiency of two balancing approaches on three imbalanced PSG datasets (CCSHS, Sleep-EDF, and Sleep-EDF-V1). The qualitative and quantitative evaluation of experimental results demonstrates that the proposed methods could not only show the superiority of class balancing through the confusion matrix and classwise metrics, but also get better N1 stage and whole stages classification accuracies compared to other state-of-the-art approaches.
