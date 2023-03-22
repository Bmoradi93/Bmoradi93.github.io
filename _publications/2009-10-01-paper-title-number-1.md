---
title: "Robot to Human Object Handover Using Vision and Joint Torque Sensor Modalities"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: ''
date: 2023-1-01
venue: 'Journal 1'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-031-26889-2_11'
citation: 'Mohandes, M., Moradi, B., Gupta, K., Mehrandezh, M. (2023). Robot to Human Object Handover Using Vision and Joint Torque Sensor Modalities. In: , et al. Robot Intelligence Technology and Applications 7. RiTA 2022. Lecture Notes in Networks and Systems, vol 642. Springer, Cham. https://doi.org/10.1007/978-3-031-26889-2_11'
---
We present a robot-to-human object handover algorithm and implement it on a 7-DOF arm equipped with a 3-finger mechanical hand. The system performs a fully autonomous and robust object handover to a human receiver in real-time. Our algorithm relies on two complementary sensor modalities: joint torque sensors on the arm and an eye-in-hand RGB-D camera for sensor feedback. Our approach is entirely implicit, i.e., there is no explicit communication between the robot and the human receiver. Information obtained via the aforementioned sensor modalities are used as inputs to their related deep neural networks. While the torque sensor network detects the human receiver’s “intention” such as: pull, hold, or bump, the vision sensor network detects if the receiver’s fingers have wrapped around the object. Networks’ outputs are then fused, based on which a decision is made to either release the object or not. Despite substantive challenges in sensor feedback synchronization, object and human hand detection, our system achieves robust robot-to-human handover with 98% accuracy in our preliminary real experiments using human receivers.

[Download paper here](https://arxiv.org/pdf/2210.15085)

Recommended citation: 