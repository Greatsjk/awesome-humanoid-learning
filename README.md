# awesome-humanoid-learning [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of resources relevant to humanoid robots learning.

Given the similarities between the locomotion of humanoid robots and bipedal robots, we have included some works on bipedal locomotion for reference.

## Robot models

### Bipeds

| Name | Maker | Formats | License | Meshes | Inertias | Collisions |
|------|-------|---------|---------|--------|----------|------------|
| Bolt | ODRI | [URDF](https://github.com/Gepetto/example-robot-data/tree/master/robots/bolt_description) | BSD-3-Clause | ✔️ | ✔️ | ✔️ |
| Cassie (MJCF) | Agility Robotics | [MJCF](https://github.com/deepmind/mujoco_menagerie/tree/main/agility_cassie) | MIT | ✔️ | ✔️ | ✔️ |
| Cassie (URDF) | Agility Robotics | [URDF](https://github.com/robot-descriptions/cassie_description) | MIT | ✔️ | ✔️ | ✔️ |
| Spryped | Benjamin Bokser | [URDF](https://github.com/bbokser/spryped/tree/master/spryped_urdf_rev06) | GPL-3.0 | ✔️ | ✔️ | ✔️ |
| Upkie | Tast's Robots | [URDF](https://github.com/tasts-robots/upkie_description) | Apache-2.0 | ✔️ | ✔️ | ✔️ |

### Humanoids

| Name | Maker | Formats | License | Meshes | Inertias | Collisions |
|------|-------|---------|---------|--------|----------|------------|
| Atlas DRC (v3) | Boston Dynamics | [URDF](https://github.com/RobotLocomotion/drake/tree/master/examples/atlas) | BSD-3-Clause | ✔️ | ✔️ | ✔️ |
| Atlas v4 | Boston Dynamics | [URDF](https://github.com/openai/roboschool/tree/1.0.49/roboschool/models_robot/atlas_description) | MIT | ✔️ | ✔️ | ✔️ |
| Digit | Agility Robotics | [URDF](https://github.com/adubredu/DigitRobot.jl) | ✖️ | ✔️ | ✔️ | ✔️ |
| iCub | IIT | [URDF](https://github.com/robotology/icub-models/tree/master/iCub) | CC-BY-SA-4.0 | ✔️ | ✔️ | ✔️ |
| JAXON | JSK | [COLLADA](https://github.com/stephane-caron/openrave_models/tree/master/JAXON), [URDF](https://github.com/robot-descriptions/jaxon_description), [VRML](https://github.com/start-jsk/rtmros_choreonoid/tree/master/jvrc_models/JAXON_JVRC) | CC-BY-SA-4.0 | ✔️ | ✔️ | ✔️ |
| JVRC-1 | AIST | [MJCF](https://github.com/isri-aist/jvrc_mj_description/), [URDF](https://github.com/stephane-caron/jvrc_description) | BSD-2-Clause | ✔️ | ✔️ | ✔️ |
| NAO | SoftBank Robotics | [URDF](https://github.com/ros-naoqi/nao_robot/tree/master/nao_description/urdf/naoV50_generated_urdf), [Xacro](https://github.com/ros-naoqi/nao_robot/tree/master/nao_description/) | BSD-3-Clause | [:heavy_minus_sign:](https://github.com/ros-naoqi/nao_meshes#readme) | ✔️ | ✔️ |
| Robonaut 2 | NASA JSC Robotics | [URDF](https://github.com/gkjohnson/nasa-urdf-robots/tree/master/r2_description) | NASA-1.3 | ✔️ | ✔️ | ✔️ |
| Romeo | Aldebaran Robotics | [URDF](https://github.com/ros-aldebaran/romeo_robot/tree/master/romeo_description) | BSD-3-Clause | ✔️ | ✔️ | ✔️ |
| SigmaBan | Rhoban | [URDF](https://github.com/Rhoban/sigmaban_urdf) | MIT | ✔️ | ✔️ | ✔️ |
| TALOS | PAL Robotics | [URDF](https://github.com/stack-of-tasks/talos-data) | LGPL-3.0 | ✔️ | ✔️ | ✔️ |
| Valkyrie | NASA JSC Robotics | [URDF](https://github.com/gkjohnson/nasa-urdf-robots/tree/master/val_description/model), [Xacro](https://gitlab.com/nasa-jsc-robotics/val_description) | NASA-1.3 | ✔️ | ✔️ | ✔️ |
| WALK-MAN | IIT | [Xacro](https://github.com/ADVRHumanoids/iit-walkman-ros-pkg/tree/master/walkman_urdf) | BSD-3-Clause | ✔️ | ✔️ | ✔️ |
| H1 | Unitree | [MJCF](https://github.com/google-deepmind/mujoco_menagerie/tree/main/unitree_h1) | BSD-3-Clause | ✔️ | ✔️ | ✔️ |
 
## News

- **[20240116]** Tesla Optimus Bot Folds Laundry [ [X](https://twitter.com/elonmusk/status/1746970616060580326) | [Video](https://www.youtube.com/watch?v=gyURDZB7imo) ]

## Papers

### 2023


- [2023] Learning Bipedal Walking for Humanoids with Current Feedback. [[paper](https://arxiv.org/pdf/2303.03724.pdf)] [[code](https://github.com/rohanpsingh/LearningHumanoidWalking/tree/topic/omnidirectional-walk)]

- [2023] Learning Humanoid Locomotion with Transformers. [[paper](https://arxiv.org/pdf/2303.03381.pdf)]

- [**ICRA**] Benchmarking Potential Based Rewards for Learning Humanoid Locomotion. [[paper](https://ieeexplore.ieee.org/abstract/document/10160885)]

- [**IEEE-RAL**] Learning Complex Motor Skills for Legged Robot Fall Recovery. [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10138662)]

### 2022


- [2022] MoCapAct: A Multi-Task Dataset for Simulated Humanoid Control. [**imitation**] [[paper](https://arxiv.org/pdf/2208.07363.pdf)] [[project](https://microsoft.github.io/MoCapAct/)]

- [2022] Imitate and Repurpose: Learning Reusable Robot Movement Skills From Human and Animal Behaviors. [**imitation**] [[paper](https://arxiv.org/abs/2203.17138)]

- [2022] NeRF2Real: Sim2real Transfer of Vision-guided Bipedal Motion Skills using Neural Radiance Fields. [[paper](https://arxiv.org/pdf/2210.04932.pdf)]

- [2022] Learning Bipedal Walking On Planned Footsteps For Humanoid Robots. [[paper](https://arxiv.org/pdf/2207.12644.pdf)] [[code](https://github.com/rohanpsingh/LearningHumanoidWalking)]

- [2022] Dynamic Bipedal Maneuvers through Sim-to-Real Reinforcement Learning. [[paper](https://arxiv.org/abs/2207.07835)]

- [2022] Sim-to-Real Learning of Compliant Bipedal Locomotion on Torque Sensor-Less Gear-Driven Humanoid. [[paper](https://arxiv.org/abs/2204.03897)]

- [**PMLR**] Towards Real Robot Learning in the Wild: A Case Study in Bipedal Locomotion. [[paper](https://proceedings.mlr.press/v164/bloesch22a/bloesch22a.pdf)]

- [**PMLR**] Learning to Walk in Minutes Using Massively Parallel Deep Reinforcement Learning. [**platform**] [[paper](https://proceedings.mlr.press/v164/rudin22a/rudin22a.pdf)] [[code](https://github.com/leggedrobotics/legged_gym)]

- [**ICRA**] Sim-to-Real Learning of Footstep-Constrained Bipedal Dynamic Walking. [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9812015)]


- [**ACM GRAPH**] ASE: Large-Scale Reusable Adversarial Skill Embeddings for Physically Simulated Characters [[paper](https://dl.acm.org/doi/pdf/10.1145/3528223.3530110)]

- [**ICMA**] Custom Sine Waves Are Enough for Imitation Learning of Bipedal Gaits with Different Styles. [[paper](https://arxiv.org/abs/2204.04157)]

- [**Machines**] Deep Reinforcement Learning for Model Predictive Controller Based on Disturbed Single Rigid Body Model of Biped Robots. [[paper](https://www.mdpi.com/2075-1702/10/11/975)]

- [**IEEE-RAS**] Improving Sample Efficiency of Deep Reinforcement Learning for Bipedal Walking. [[paper](https://ieeexplore.ieee.org/document/10000068)] [[code](https://github.com/rgalljamov/learn2walk)] 

- [**IEEE-RAS**] Dynamic Bipedal Turning through Sim-to-Real Reinforcement Learning. [[paper](https://ieeexplore.ieee.org/abstract/document/10000225)]

- [**IEEE-RAS**] Learning Bipedal Walking On Planned Footsteps For Humanoid Robots. [[paper](https://arxiv.org/pdf/2207.12644.pdf)] [[code](https://github.com/rohanpsingh/learninghumanoidwalking)]

- [**TCAS-II**] Parallel Deep Reinforcement Learning Method for Gait Control of Biped Robot. [[paper](https://ieeexplore.ieee.org/document/9690599)]

- [**IEEE-RAL**] Linear Policies are Sufficient to Realize Robust Bipedal Walking on Challenging Terrains. [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9682564)]



### 2021


- [**ICRA**] Reinforcement Learning for Robust Parameterized Locomotion Control of Bipedal Robots. [**sim2real**] [[paper](https://ieeexplore.ieee.org/abstract/document/9560769)]

- [**ICRA**] Sim-to-Real Learning of All Common Bipedal Gaits via Periodic Reward Composition. [[paper](https://arxiv.org/abs/2011.01387)]

- [**ICRA**] Deepwalk: Omnidirectional bipedal gait by deep reinforcement learning. [[paper](https://www.ais.uni-bonn.de/papers/ICRA_2021_Rodriguez.pdf)]

- [**IROS**] Robust Feedback Motion Policy Design Using Reinforcement Learning on a 3D Digit Bipedal Robot. [[paper](https://ieeexplore.ieee.org/abstract/document/9636467)]

- [**RSS**] Blind Bipedal Stair Traversal via Sim-to-Real Reinforcement Learning. [[paper](https://www.ais.uni-bonn.de/papers/ICRA_2021_Rodriguez.pdf)]

- [**ICRA**] Learning Task Space Actions for Bipedal Locomotion [[paper](https://arxiv.org/pdf/2011.04741.pdf)]


### 2020

- [**RSS**] Learning Memory-Based Control for Human-Scale Bipedal Locomotion. [**sim2real**] [[paper](https://arxiv.org/abs/2006.02402)] [[unofficial_code](https://github.com/osudrl/RSS-2020-learning-memory-based-control)]


- [**PMLR**] Learning Locomotion Skills for Cassie: Iterative Design and Sim-to-Real. [[paper](http://proceedings.mlr.press/v100/xie20a/xie20a.pdf)]


- [**IEEE-RAL**] Learning Natural Locomotion Behaviors for Humanoid Robots Using Human Bias. [[paper](https://ieeexplore.ieee.org/document/8990011)]

### 2019


- [**IROS**] Sim-to-Real Transfer for Biped Locomotion. [[paper](https://ieeexplore.ieee.org/abstract/document/8968053)]




- [**Science Robotics**] Learning Agile and Dynamic Motor Skills for Legged Robots. [[paper](https://arxiv.org/pdf/1901.08652.pdf)] [[code](https://github.com/junja94/anymal_science_robotics_supplementary)]



### 2018



- [**IEEE RAS**] Learning Whole-body Motor Skills for Humanoids. [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8625045)]





## Related awesome-lists

- [awesome-isaac-gym](https://github.com/wangcongrobot/awesome-isaac-gym)
- [Hybrid Robotics Publications](https://hybrid-robotics.berkeley.edu/publications/)
- [Reinforcement-Learning-in-Robotics](https://github.com/Skylark0924/Reinforcement-Learning-in-Robotics)
- [bipedal-robot-learning-collection](https://github.com/zita-ch/bipedal-robot-learning-collection)
- [Awesome_Quadrupedal_Robots](https://github.com/curieuxjy/Awesome_Quadrupedal_Robots)
- [Awesome-Implicit-NeRF-Robotics](https://github.com/zubair-irshad/Awesome-Implicit-NeRF-Robotics)
- [Legged-Robots](https://github.com/singhaman1750/Legged-Robots)
- [Awesome Robot Descriptions](https://github.com/robot-descriptions/awesome-robot-descriptions)
- [awesome-legged-locomotion-learning](https://github.com/gaiyi7788/awesome-legged-locomotion-learning)