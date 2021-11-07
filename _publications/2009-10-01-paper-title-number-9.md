---
title: "Fast Sequential Feature Extraction for Recurrent Neural Network-based Hyperspectral Image Classification"
collection: publications
permalink: /publication/2020-09-04-rnn-image-classification 
excerpt: 'This paper is about a faster sequential feature extraction framework for long short-term memory (LSTM)-based HSI classification we proposed.'
date: 2020-09-04
venue: 'IEEE Transactions on Geoscience and Remote Sensing,   Ma, A., Filippi, A., Wang, Z., Yin, Z., Huo, D., Li., X., & Guneralp, B.'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9186805'

---
Abstract: Classification is a critical, widely employed type of hyperspectral image (HSI) processing. Recently, deep learning models have been attracting more attention within the hyperspectral remote-sensing community due to their improved classification performance. Among them, recurrent neural networks (RNNs), which were initially used to handle sequential data, have been applied to HSI classification with promising results. The key point for such RNN-based models in a classification context is the extraction of a sequential feature for each individual pixel in a HSI. One popular strategy is to first extract similar pixels compared with a target pixel from the HSI, and then use those similar pixels to encode its sequential feature. However, the computational cost is tremendous, especially if such similarity-calculation search is done on the whole image. In this article, inspired by our previous work regarding similarity measurement-based sequential feature construction, a faster sequential feature extraction framework for long short-term memory (LSTM)-based HSI classification is proposed, where object-based segmentation method is employed for the purpose of imposing spatial constraints and computational acceleration. Within the proposed framework, both the local segment containing the target pixel and nonlocal segments are considered. For a target pixel, similar segments are selected first based on segment-based features, and then similar pixels from selected segments are extracted to construct a sequential feature. During pixel-wise similarity measurement, both spectral and spatial information are considered in such computation. Experimental results on three benchmark HSI data sets illustrate that the proposed methods achieve promising classification performance with markedly lower computation-time cost.

[Download paper here](https://ieeexplore.ieee.org/abstract/document/9186805)
