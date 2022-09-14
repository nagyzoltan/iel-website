---
title: "New Paper: Real-world challenges for multi-agent reinforcement learning
  in grid-interactive buildings"
subtitle: ""
date: 2022-09-14T20:15:26.216Z
summary: ""
draft: false
featured: false
image:
  filename: 1-s2.0-s2666546822000489-ga1_lrg.jpg
  focal_point: Smart
  preview_only: false
---
Led by IEL's awesome PhD Student Kingsley, we have a new paper in Energy and AI.

Open Access: https://www.sciencedirect.com/science/article/pii/S2666546822000489

**Title:** Real-world challenges for multi-agent reinforcement learning in grid-interactive buildings

**Abstract:**

Building upon prior research that highlighted the need for standardizing environments for building control research, and inspired by recently introduced challenges for real life reinforcement learning (RL) control, here we propose a non-exhaustive set of nine real world challenges for RL control in grid-interactive buildings (GIBs). We argue that research in this area should be expressed in this framework in addition to providing a standardized environment for repeatability. Advanced controllers such as model predictive control (MPC) and RL control have both advantages and disadvantages that prevent them from being implemented in real world problems. Comparisons between the two are rare, and often biased. By focusing on the challenges, we can investigate the performance of the controllers under a variety of situations and generate a fair comparison. As a demonstration, we implement the offline learning challenge in CityLearn, an OpenAI Gym environment for the easy implementation of RL agents in a demand response setting to reshape the aggregated curve of electricity demand by controlling the energy storage of a diverse set of buildings in a district, and study the impact of different levels of domain knowledge and complexity of RL algorithms. We show that the sequence of operations utilized in a rule based controller (RBC) used for offline training affects the performance of the RL agents when evaluated on a set of four energy flexibility metrics. Longer offline learning from an optimized RBC leads to improved performance in the long run. RL agents that learn from a simplified RBC risk poorer performance as the offline learning period increases. We also observe no impact on performance from information sharing amongst agents. We call for a more interdisciplinary effort of the research community to address the real world challenges, and unlock the potential of GIB controllers.