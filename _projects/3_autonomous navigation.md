---
layout: page
title: Autonomous Navigation
description: UAV navigation using deep reinforcement learning
img: assets/img/projects/quadrotor_1.jpeg
importance: 3
category: work
---
Developed a platform for training UAV navigation policies in complex unknown environment.

- An Open AI Gym env is created include kinematic models for both multirotor and fixed-wing UAVs.
- Some UE4 environments are provided to train and test the navigation policy.
- Based on AirSim and SB3.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/3_autonomous_fligt/result_3d_NH_multirotor.gif" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Autonomous flight with trained network.
</div>
