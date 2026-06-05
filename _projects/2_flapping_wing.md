---
layout: page
title: Flapping-Wing UAV Autonomous Obstacle Avoidance
description: Bio-inspired monocular perception, image stabilization, reinforcement learning, and real-flight validation for a bird-like flapping-wing micro UAV.
img: assets/img/projects/flapping_wing_1.jpeg
importance: 2
category: work
---

This project studied autonomous obstacle avoidance for a bird-like flapping-wing micro aerial vehicle. Unlike multirotor UAVs, flapping-wing aircraft have severe constraints in size, payload, onboard computation, and image stability, while still needing fast perception, planning, and control during forward flight.

The platform had a total takeoff weight of about 250 g, a payload budget of about 20 g, and a flight speed of around 10 m/s. These constraints made common stereo or depth-camera solutions unsuitable, so the system used a lightweight monocular camera and a bio-inspired perception pipeline.

Key technical components:

- Bio-inspired monocular obstacle perception based on the LGMD mechanism, inspired by insect compound-eye neural responses to looming objects.
- IMU-assisted image stabilization to reduce flapping-induced pitch oscillation and improve monocular perception reliability.
- AirSim-based simulation training for constant-altitude obstacle avoidance, where the UAV avoided trees through roll commands while flying toward a target.
- Deep reinforcement learning policy training and deployment to real-world flight tests.
- Real-flight validation on the "Xinge" flapping-wing UAV, with 10 minutes of flight time and 14 autonomous-mode switches, all completing obstacle avoidance successfully.

<div class="row text-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/flapping_wing/platform.png" title="Flapping-wing UAV platform" class="img-fluid rounded z-depth-1" max-width="50%" %}
    </div>
</div>
<div class="caption">
    Bird-like flapping-wing UAV platform used for autonomous obstacle avoidance experiments.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/flapping_wing/lgmd_response.png" title="LGMD response" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Bio-inspired LGMD perception: looming obstacles generate progressively stronger visual responses before collision.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/flapping_wing/pitch_stabilization.png" title="Pitch stabilization result" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
    IMU-assisted monocular image stabilization reduced the effect of flapping-induced pitch oscillation on visual perception.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/flapping_wing/airsim_training.png" title="AirSim training environment" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    AirSim simulation environment for reinforcement-learning-based obstacle avoidance training.
</div>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/flapping_wing/real_flight_test.png" title="Real flight test" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Real-world autonomous obstacle avoidance flight test at Northwestern Polytechnical University. 2023.03.31
</div>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/flapping_wing.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>
<div class="caption">
    Flight test video: autonomous obstacle avoidance with a bird-like flapping-wing UAV.
</div>
