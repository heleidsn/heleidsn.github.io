---
layout: page
title: Aerial Manipulator
description: Adaptive whole-body control and MPC-based flight experiments for aerial manipulation.
img: assets/img/projects/am_1.png
importance: 1
category: work
# related_publications: true
---

Aerial manipulators combine quadrotors with robotic arms for inspection, manipulation, transportation, and contact-rich interaction in hard-to-reach environments.

Accurate trajectory tracking is challenging because the arm motion and grasped payload introduce strong dynamic coupling, changing inertia, and external disturbances during flight.

This project develops an adaptive whole-body control framework with real-time MPC-based trajectory tracking for aerial manipulation. We designed and built a customized prototype, implemented simulation software for controller evaluation, and validated the system through initial grasping and flight tests.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/am_1.png" title="Aerial manipulator prototype" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Customized aerial manipulator prototype.
</div>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/aerial_manipulator_test_1.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>
<div class="caption">
    Initial flight test at National University of Singapore. 2025.01.11
</div>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/20250609 simulation grasp success.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>
<div class="caption">
    Simulation test for grasping and manipulation. 2025.06.09
</div>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/20250615 real flight L1+MPC grasp success.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>
<div class="caption">
    Real flight grasping experiment with L1 adaptive control and MPC tracking. 2025.06.15
</div>
