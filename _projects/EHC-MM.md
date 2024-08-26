---
layout: page
title: EHC-MM
description: Embodied Holistic Control for Robotic Mobile Manipulation
img: assets/img/EHC-MM/teaser.png
importance: 1
category: Robotics
related_publications: 
---



Mobile Manipulation (MM), with their blend of mobility and dexterity, are increasingly poised to undertake various domestic tasks. Mobile Manipulation typically entails the base for mobility, the arm for precision grasping, and the camera for perception. It is aligned with the embodied principle of _Distant Mobility, Close Grasping_(DMCG) when implementing holistic control. We propose _Embodied Holistic Control_ for Mobile Manipulation: In terms of control, we optimize the velocity controller to ensure that the velocity output aligns with the DMCG. In terms of perception, to address reactive tasks, we introduce monitor-based servoing, enabling continuous monitoring of the target, avoiding the loss of target. This approach allows coordinated control between the robot's base, arm, and camera. Additionally, we present GS-Net* that improves grasping stability. Through extensive simulated and real-world experiments, our approach markedly enhances the success rates and efficiency in mobile manipulation, achieving a **95.6%** grasping success rate in real-world settings, with a **52.8%** time efficiency boost.

<div class="row">
    <div class="col-sm mt-3 mt-md-0 text-center">
        {% include figure.html path="assets/img/EHC-MM/teaser.png" title="EHC-MM" class="img-fluid rounded z-depth-1" width="80%" caption="Mobile manipulation often adheres to the DMCG principle, prioritizing base movement when at a distance and focusing on arm grasping when close. This enables the robot to achieve higher precision and efficiency."%}
    </div>
</div>


**Video**
<iframe width="560" height="315" src="https://www.youtube.com/embed/DrJD_Djxj-E?si=Z5f4Shq9_NxREy-k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>