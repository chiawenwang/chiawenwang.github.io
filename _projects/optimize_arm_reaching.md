---
layout: page
title: Optimize arm reaching
description: Optimizing Robot Arm Reaching Ability with Different Joints Functionality
img: assets/img/optimize_arm_reaching/show.jpg
importance: 4
category: Robotics
related_publications: 
---



During the process of reaching a target, a robotic arm may generate a large number of redundant movements due to the stochastic nature of planning algorithms. We think that each joint of the robotic arm has a unique functionality towards the arm's end effector. Therefore, during motion planning, we optimized the weights of each joint based on its individual *functionality*. We introduce the human arm *operation mechanism* - When a person is reaching for a distant target, the shoulder-near joints take on more actions. We proposed an advanced auxiliary loss function. By utilizing this function, we can filter out multiple solutions from the inverse model, thus reducing the amount of joint change and redundant movements. We conducted comprehensive comparative experiments on the UR3 robotic arm, and the results showed that our approach achieved better efficiency and outcomes.

<div class="row">
    <div class="col-sm mt-3 mt-md-0 text-center">
        {% include figure.liquid path="assets/img/optimize_arm_reaching/teaser.png" title="" class="img-fluid rounded z-depth-1" width="80%" caption="Human arm operation mechanism. People tend to use their shoulder-near joints more when reaching distant targets."%}
    </div>
</div>

**Video**
<iframe width="560" height="315" src="https://www.youtube.com/embed/CR-yqj9y6qI?si=v9xR6FdBS0Ey5iKJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
