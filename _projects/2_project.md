---
layout: page
title: Obstacle detection by LiDAR
description: Efficient LiDAR-based In-water Obstacle Detection and Segmentation by Autonomous Surface Vehicles in Aquatic Environments
img: assets/img/LIDAR/beauty.png
importance: 1
category: work
---

```
To reduce the computational requirement, our method first converts the 3D point cloud 
into a 2D spherical projection image. Then, an algorithm based on the integration of 
a breadth-first search and a variant of a hierarchical agglomerative clustering 
segments the points according to different objects. 
Our method addresses the sparsity and instability of the point cloud in the aquatic domain 
(a characteristic that makes the methods developed for self-driving cars 
not directly applicable for in-water obstacle segmentation) 
as demonstrated in our experiments.
```

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/LIDAR/catabot.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/LIDAR/beauty.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
Robotic boat Catabot with Velodyne VLP-16 scanner (left) performs LiDAR-based obstacle detection and segmentation based on the spherical projection image (right).
</div>

Here is a video I have presented at IROS2021.
<p style="text-align: center;">
<!-- youtube embedding -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/V9w549rVkdI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>