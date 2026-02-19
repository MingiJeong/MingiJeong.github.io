---
layout: page
title: Risk- and Energy-Aware Navigation
description: RENEW Risk- and Energy-Aware Navigation in Dynamic Waterways
img: assets/img/RENEW/renew.gif
importance: 2
category: work
---

```
We present RENEW, a novel global path planning frame- work for Autonomous Surface Vehicle (ASV) operating in
dynamic environments with external disturbances (e.g., water currents). These disturbances significantly affect both the
risk and energy cost of navigation, particularly in constrained coastal waterways, by dynamically reshaping the navigable
area. RENEW addresses this challenging scenario through a unified, risk- and energy-aware planning strategy that guar-
antees safety by explicitly identifying states at risk of entering non-navigable regions and enforcing adaptive safety con-
straints. Our planner incorporates a best-effort strategy under worst-case scenarios, inspired by contingency planning
concepts from maritime domains, to ensure feasible control actions even under adverse conditions. RENEW employs a
hierarchical architecture: a high-level planner explores topologically distinct paths via constrained triangulation, while
a low-level planner selects an energy-efficient and kinematically feasible trajectory within a safe corridor. We validate
our approach through extensive simulations using both custom realistic scenarios and real-world ocean current data. To
our knowledge, this is the first global planning framework to jointly address the adaptive identification of non-navigable
areas and topological diversity within a risk-aware paradigm, enabling robust navigation in maritime environments.
```

<div class="row">
    {% include figure.html path="assets/img/RENEW/renew-beauty.png" title="example image" class="img-fluid rounded z-depth-1" %}
</div>
<div class="caption">
Path planning under external disturbances. (Top) Our method selects energy-efficient paths across multiple homotopy classes, using current-based adaptive padding (gray) around obstacles (brown), to ensure feasible contingency maneuvers. (Bottom) The baseline prioritizes distance over energy/homotopy. Without adaptive padding, its paths lack safety margins for contingency maneuvers.
</div>

Here is a video I have presented at AAAI2026. Our paper was selected for an oral presentation! 🎉
<p style="text-align: center;">
<!-- youtube embedding -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/q8O7W_63Xv8?si=EvJ46ClzlzzUf4XY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</p>