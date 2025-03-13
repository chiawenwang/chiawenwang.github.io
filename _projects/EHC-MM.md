---
layout: page
title: EHC-MM
description: Embodied Holistic Control for Mobile Manipulation
img: assets/img/EHC-MM/teaser4.png
importance: 1
category: Robotics
related_publications: 
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0 text-center">
        {% include figure.html path="assets/img/EHC-MM/teaser4.png" title="EHC-MM" class="img-fluid rounded z-depth-1" height="80%" caption="Real-world scenarios"%}
    </div>

    <div class="col-sm mt-3 mt-md-0 text-center">
        {% include figure.html path="assets/img/EHC-MM/teaser5.png" title="EHC-MM" class="img-fluid rounded z-depth-1" height="80%" caption="Simulation"%}
    </div>
</div>

Mobile manipulation typically entails the base for mobility, the arm for accurate manipulation, and the camera for perception. It is necessary to follow the principle of *Distant Mobility, Close Grasping* (DMCG) in holistic control. We propose **Embodied Holistic Control for Mobile Manipulation (EHC-MM)** with the embodied function of **sig(*w*)**: By formulating the DMCG principle as a Quadratic Programming (QP) problem, **sig(*w*)** dynamically balances the robot’s emphasis between movement and manipulation, considering the robot's state and environment. In addition, we propose the **Monitor-Position-Based Servoing (MPBS)** with **sig(*w*)**, enabling the tracking of the target during the operation. This approach allows coordinated control between the robot's base, arm, and camera. Through extensive simulations and real-world experiments, our approach significantly improves both the success rate and efficiency of mobile manipulation tasks, achieving a **95.6% success rate** in real-world scenarios and a **52.8% increase in time efficiency**.


<!-- Mobile Manipulation (MM), with their blend of mobility and dexterity, are increasingly poised to undertake various domestic tasks. Mobile Manipulation typically entails the base for mobility, the arm for precision grasping, and the camera for perception. It is aligned with the embodied principle of _Distant Mobility, Close Grasping_(DMCG) when implementing holistic control. We propose _Embodied Holistic Control_ for Mobile Manipulation: In terms of control, we optimize the velocity controller to ensure that the velocity output aligns with the DMCG. In terms of perception, to address reactive tasks, we introduce monitor-based servoing, enabling continuous monitoring of the target, avoiding the loss of target. This approach allows coordinated control between the robot's base, arm, and camera. Additionally, we present GS-Net* that improves grasping stability. Through extensive simulated and real-world experiments, our approach markedly enhances the success rates and efficiency in mobile manipulation, achieving a **95.6%** grasping success rate in real-world settings, with a **52.8%** time efficiency boost. -->




<div class="row">
    <div class="col-sm mt-3 mt-md-0 text-center">
        {% include figure.html path="assets/img/EHC-MM/framework1.png" title="EHC-MM" class="img-fluid rounded z-depth-1" width="80%" caption="Framework of EHC-MM."%}
    </div>
</div>


**Video**

<iframe width="560" height="315" src="https://www.youtube.com/embed/ityJTxbnnao?si=esj4KzdRBVv07Amx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


<h2>Reference</h2>
<p>If you find our work useful, please cite:</p>
<pre><code>
@misc{wang2025ehcmmembodiedholisticcontrol,
      title={EHC-MM: Embodied Holistic Control for Mobile Manipulation}, 
      author={Jiawen Wang and Yixiang Jin and Jun Shi and Yong A and Dingzhe Li and Fuchun Sun and Dingsheng Luo and Bin Fang},
      year={2025},
      eprint={2409.08527},
      archivePrefix={arXiv},
      primaryClass={cs.RO},
      url={https://arxiv.org/abs/2409.08527}
}
</code></pre>