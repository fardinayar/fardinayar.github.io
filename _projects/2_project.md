---
layout: page
title: Object Depth Anything - Monocular Object Depth Estimation
description: Self-supervised monocular object depth estimation combining MonoDepth2 and DepthAnything
img: assets/img/3.jpg
importance: 2
category: research
giscus_comments: true
related_publications: true
github: https://github.com/fardinayar/object_depth_anything
---

Object Depth Anything is an innovative project that combines MonoDepth2 and DepthAnything for self-supervised monocular object depth estimation. The method leverages DepthAnything's pre-trained Vision Transformer as encoder and incorporates GPS loss from G2S to predict accurate metric depth, while integrating YOLOv8 for object detection trained on COCO dataset. This hybrid approach achieves superior performance on the KITTI dataset with improved metrics (abs_rel: 0.101, rmse: 4.579) compared to baseline methods, making it valuable for autonomous vehicles, robotics, augmented reality, and surveillance systems requiring object-aware depth estimation.

🔗 **[View on GitHub](https://github.com/fardinayar/object_depth_anything)**
