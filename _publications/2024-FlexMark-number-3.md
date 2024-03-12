---
title: "FlexMark: Adaptive Watermarking Method for Images"
collection: publications
permalink: /publications/20240-FlexMark-number-3
venue: "ACM Multimedia Systems"
excerpt: 'We proposed a flexible watermarking method that can be used in different scenarios from copyright protection to data hiding.'
date: 2024-04-13
paperurl: 
citation: 'M. Arab, et al. 2024. FlexMark: Adaptive Watermarking Method for Images. In Proceedings of the 15th ACM Multimedia Systems Conference. '
---

## Abstract
Most current watermarking methods offer low and fixed capacity, which means they can only embed small-size watermarks into images. Additionally, they are typically robust to only a small subset of the known image transformations (aka distortions) that occur during the processing, transmission, and storage of images. These shortcomings limit their adoption in many practical multimedia applications. \revised{We propose FlexMark, a robust and adaptive watermarking method for images, which achieves a better capacity-robustness trade-off than current methods and can easily be used for different applications. FlexMark categorizes and models the fundamental aspects of various image transformations, enabling it to achieve high accuracy in the presence of many practical transformations. FlexMark introduces new ideas to further improve the performance, including double-embedding of the input message, employing self-attention layers to identify the most suitable regions in the image to embed the watermark bits, and utilization of a discriminator to improve the visual quality of watermarked images. In addition, FlexMark offers a parameter, alpha, to enable users to control the trade-off between robustness and capacity to meet the requirements of different applications.}  We implement FlexMark and assess its performance using datasets commonly used in this domain. Our results show that FlexMark is robust against a wide range of image transformations, including ones that were never seen during its training, which shows its generality and practicality. Our results also show that FlexMark substantially outperforms the closest methods in the literature in terms of capacity and robustness. 