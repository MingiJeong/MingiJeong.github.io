---
layout: page
title: Intention-aware action
description: Active Learning-augmented Intention-aware Obstacle Avoidance of Autonomous Surface Vehicles in High-traffic Waters
img: assets/img/intent-aware/intent-cover2.gif
importance: 1
category: work
---

```
This paper enhances the obstacle avoidance of Autonomous Surface Vehicles (ASVs) 
for safe navigation in high-traffic waters with an active state estimation of 
obstacle's passing intention and reducing its uncertainty. 

Our main contributions are:
(a) topological modeling of passing based on maritime navigation's 
inherent conceptual topolog and implementation of LSTM-backbone-based intention classification
(b) a novel multi-objective local planner that includes an active strategy 
to increase information gain in uncertain encounters about the passing intention 
of obstacles, while ensuring collision avoidance; and
(c) implementation in Robot Operating System (ROS) with comprehensive analysis 
through extensive Monte Carlo simulations, experiments in the ocean with a real ASV, 
and a real-world accident case study successfully demonstrating safe and real-time collision avoidance. 
```

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/intent-aware/intent-beauty-state-of-the-art.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/intent-aware/intent-beauty-ours.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Controlled ASV, R's collision avoidance by state-of-the-art method vs.proposed method using active learning-augmented intention-awareness under an uncertain scenario where an obstacle, O approaches from the left side of R.
</div>

Here is a video I have presented at IROS2024.
<p style="text-align: center;">
<iframe width="560" height="315" src="https://www.youtube.com/embed/0W0d4MurzzA?si=zI_iVXQIs6tLhxg2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>