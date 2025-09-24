---
layout: page
title: Operation Point Selection
description: A Novel Learning-based Approach for Dual-Arm Robot Operation Point Selection
img: assets/img/operation_point_selection/show.jpg
importance: 3
category: Robotics
related_publications: 
---



In the scenario of dual-arm robot collaborative manipulation, selecting the appropriate operation point can significantly influence the success rate and efficiency of the subsequent tasks. In our context, the so-called *operation point*, instead of manipulation points, refers to the three-dimensional positions in the workspace where the dual-arm robot performs its tasks. In this paper, we propose a novel learning-based approach for selecting the optimal operation point. Meanwhile, we design a specific measure to evaluate the selection of the dual-arm operation point. In the model training process, our approach enables the dual-arm robot to autonomously explore the workspace to try its best to find the most suitable operation point. To better validate our proposed approach, we designed a dual-arm robot platform that includes both the UR3 and AUBO i5 robotic arms, rather than two robotic arms with the same configuration. The experiment was conducted on the peg-in-hole assembly task. To efficiently train our model, we also established a corresponding simulation environment. The experimental results show that our approach has better performance in selecting operation points than traditional baseline approaches.

<div class="row">
    <div class="col-sm mt-3 mt-md-0 text-center">
        {% include figure.liquid path="assets/img/operation_point_selection/teaser.png" title="" class="img-fluid rounded z-depth-1" width="80%" caption="Different operation points correspond to different dual-arm postures. On the left, the selected operation point is too low, causing the distance between the joints of the robot arm too close, which may directly lead to the failure of the subsequent task. In contrast, on the right, the robot arm has a more relaxed posture that conforms to the idea of human dual-arm operations, which is conducive to the success of the subsequent task."%}
    </div>
</div>


**Video**
<iframe width="560" height="315" src="https://www.youtube.com/embed/CR-yqj9y6qI?si=GnCieur_TfKVOAI1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
