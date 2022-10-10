---
layout: page
title: Multiple obstacle avoidance
description: Motion Attribute-based Clustering and Collision Avoidance of Multiple In-water Obstacles by Autonomous Surface Vehicle
img: assets/img/MOA/moa-new-trial1_15,20,15.gif
importance: 1
category: work
---

```
Our work proposes a novel real-time non-myopic obstacle avoidance method, 
allowing an ASV that has only partial knowledge of the surroundings
within the sensor radius to navigate in high-traffic maritime scenarios. 
By using
(1) a clustering method based on motion attributes of other obstacles; 
(2) a geometric framework for identifying the feasible action space; and 
(3) a multi-objective optimization to determine the best action
```

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/MOA/state-of-the-art.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/MOA/proposed.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Collision avoidance behavior for controlled ASV, using state-of-the art (left) vs. proposed method (right)
    under congested traffic with multiple obstacles 
</div>

Here is a video I have presented at IROS2022.
<p style="text-align: center;">
<iframe width="560" height="315" src="https://www.youtube.com/embed/a305lja1lfk" 
title="YouTube video player" 
frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>

<!-- You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal its glory in the next row of images.
 -->

<!-- The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above: -->

