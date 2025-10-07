---
layout: page
title: LiDAR-Camera Fusion for Video Panoptic Segmentation
description: Novel approach for combining LiDAR and camera data for robust perception in autonomous vehicles
img: assets/img/12.jpg
importance: 1
category: research
related_publications: true
---

This project presents a novel approach for video panoptic segmentation using LiDAR-camera fusion without requiring video training data. The work addresses the challenge of achieving robust perception in autonomous vehicles by leveraging the complementary strengths of LiDAR and camera sensors.

## Key Contributions

- **Multi-modal Fusion**: Developed an effective framework for combining LiDAR point clouds with camera images
- **Video Segmentation**: Achieved video panoptic segmentation without video-specific training
- **Autonomous Vehicles**: Demonstrated practical applications in autonomous driving scenarios
- **Best Paper Award**: Received Bronze Best Paper Award at ICEA2024 conference

## Technical Approach

The method leverages the spatial accuracy of LiDAR data combined with the rich visual information from cameras to achieve robust segmentation across video sequences. The approach eliminates the need for video-specific training while maintaining high performance on video segmentation tasks.

## Impact

This work contributes to the advancement of autonomous vehicle perception systems by providing a more efficient and robust approach to multi-modal sensor fusion. The methodology has potential applications in various autonomous systems requiring real-time scene understanding.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="LiDAR-Camera Fusion Architecture" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="Segmentation Results" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="Autonomous Vehicle Application" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: LiDAR-Camera fusion architecture showing multi-modal data processing. Middle: Segmentation results demonstrating improved accuracy. Right: Application in autonomous vehicle perception systems.
</div>

## Publications

This work resulted in the following publication:
{% cite ayar2024lidar %}
