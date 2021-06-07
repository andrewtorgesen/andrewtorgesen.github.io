---
layout: doc
title: "Real-Time Semantic Segmentation"
subtitle: "Class project for a Machine Learning course at MIT."
featured_image: /images/projects/target_train.png
active: true
---

* * *

[Project Paper](https://andrewtorgesen.github.io/res/6.862 Final Project Report.pdf)

* * *

<iframe width="560" height="315" src="https://www.youtube.com/embed/6axVA-JcRvs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

This project seeks to improve the trade-off between run-time and accuracy of [FANet](https://arxiv.org/abs/2007.03815), a state-of-the-art algorithm aimed at real-time image segmentation on video streams. The trade-off is characterized before and after augmenting FANet to include temporal context aggregation: an extension of self-attention that considers multiple consecutive image frames during both training and inference. 

To this end, the original FANet algorithm is re-produced and trained using the CityScapes dataset (20 classes) for validation of the base implementation. Subsequently, the temporal context aggregation augmentation to FANet is presented. The agumented FANet implementation is then trained and tested on both single-frame images and video streams from a segmentation dataset created using AirSim (11 classes). Results are presented for each scenario, comparing the segmentation speed (FPS) and performance (in mean-intersection-over-union, or mIoU %) of the re-implemented FANet with the results presented in the original paper, as well as a leader board for image segmentation on the CityScapes dataset. 

The presented results and analysis suggest that temporal context aggregation is not expressive enough to consistently provide performance improvements.