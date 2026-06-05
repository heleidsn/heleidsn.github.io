---
layout: page
title: Autonomous Navigation
description: Vision-based UAV obstacle avoidance with deep reinforcement learning, imitation learning, AirSim simulation, and real-flight validation.
img: assets/img/projects/quadrotor_1.jpeg
importance: 3
category: work
# github: https://github.com/heleidsn/UAV_Navigation_DRL_AirSim
---
This project developed a learning-based local planner for UAV visual navigation and obstacle avoidance in unknown environments.

The work combines deep reinforcement learning, imitation learning, and simulation-to-real validation. A training platform was built on AirSim with OpenAI Gym-style interfaces, kinematic models for multirotor and fixed-wing UAVs, and multiple Unreal Engine environments for policy training and testing.

Key contributions:

- Built an open-source AirSim-based UAV navigation framework with 550+ GitHub stars and 70+ forks.
- Implemented multirotor, fixed-wing, and flapping-wing kinematic simulation environments.
- Trained local obstacle-avoidance policies in simulation and transferred them to real flight tests.
- Developed a training-state visualization interface for monitoring learning progress.
- Studied model interpretability using Shapley-value-based output contribution analysis, action-level explanation, and feature-correlation analysis.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/3_autonomous_fligt/result_3d_NH_multirotor.gif" title="Autonomous navigation result" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Autonomous flight with a trained neural network policy in simulation.
</div>
