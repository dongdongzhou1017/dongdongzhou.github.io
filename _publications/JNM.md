---
title: "Automatic sleep scoring: A deep learning architecture for multi-modality time series"
collection: publications
permalink: /publication/JNM
excerpt: 
date: 2021-01-15
venue: 'Journal of Neuroscience Methods'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S0165027020303940'
citation: 
---

[Paper](https://www.sciencedirect.com/science/article/pii/S0165027020303940)

Abstract:
Background: Sleep scoring is an essential but time-consuming process, and therefore automatic sleep scoring is
crucial and urgent to help address the growing unmet needs for sleep research. This paper aims to develop a
versatile deep-learning architecture to automate sleep scoring using raw polysomnography recordings.
Method: The model adopts a linear function to address different numbers of inputs, thereby extending model
applications. Two-dimensional convolution neural networks are used to learn features from multi-modality
polysomnographic signals, a “squeeze and excitation” block to recalibrate channel-wise features, together with
a long short-term memory module to exploit long-range contextual relation. The learnt features are finally fed to
the decision layer to generate predictions for sleep stages.
Result: Model performance is evaluated on three public datasets. For all tasks with different available channels,
our model achieves outstanding performance not only on healthy subjects but even on patients with sleep dis-
orders (SHHS: Acc-0.87, K-0.81; ISRUC: Acc-0.86, K-0.82; Sleep-EDF: Acc-0.86, K-0.81). The highest classifica-
tion accuracy is achieved by a fusion of multiple polysomnographic signals.
Comparison: Compared to state-of-the-art methods that use the same dataset, the proposed model achieves a
comparable or better performance, and exhibits low computational cost.
Conclusions: The model demonstrates its transferability among different datasets, without changing model ar-
chitecture or hyper-parameters across tasks. Good model transferability promotes the application of transfer
learning on small group studies with mismatched channels. Due to demonstrated availability and versatility, the
proposed method can be integrated with diverse polysomnography systems, thereby facilitating sleep monitoring
in clinical or routine care.
