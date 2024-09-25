---
layout: page
title: GauTOAO
description: Gaussian-based Task-Oriented Affordance of Objects
img: assets/img/gautoao/teaser.jpg
importance: 1
category: Robotics
related_publications: 
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0 text-center">
        {% include figure.html path="assets/img/gautoao/teaser.jpg" title="gautoao" class="img-fluid rounded z-depth-1" width="80%" caption=" When the robot is presented with a bouquet of sunflowers, its attention shifts based on the intended task. If the task is to display the flowers, the robot should focus on orienting the blossoms toward the observer. Conversely, if the task is to insert the flowers into a vase, the robot's focus shifts to aligning the flower stem with the vase's opening."%}
    </div>
</div>

When your robot grasps an object using dexterous hands or grippers, it should understand the Task-Oriented Affordances of the Object(TOAO), as different tasks often require attention to specific parts of the object. To address this challenge, we propose GauTOAO, a Gaussian-based framework for Task-Oriented Affordance of Objects, which leverages vision-language models in a zero-shot manner to predict affordance-relevant regions of an object, given a natural language query. Our approach introduces a new paradigm: "static camera, moving object," allowing the robot to better observe and understand the object in hand during manipulation. GauTOAO addresses the limitations of existing methods, which often lack effective spatial grouping, by extracting a comprehensive 3D object mask using DINO features. This mask is then used to conditionally query gaussians, producing a refined semantic distribution over the object for the specified task. This approach results in more accurate TOAO extraction, enhancing the robot’s understanding of the object and improving task performance. We validate the effectiveness of GauTOAO through real-world experiments, demonstrating its capability to generalize across various tasks.


**Video**

<iframe width="560" height="315" src="https://www.youtube.com/embed/vsTa2LBNCbE?si=gmuvM20j0C8LMnak" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>